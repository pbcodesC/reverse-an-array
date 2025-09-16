# reverse-an-array

void reverseArray(vector<int>& arr) {
    int left = 0, right = arr.size() - 1;

    while (left < right) {
        swap(arr[left], arr[right]);  // swap first and last element
        left++;
        right--;
    }
}
