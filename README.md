# reverse-an-array
 void reverseArray(vector&lt;int>&amp; arr) {     int left = 0, right = arr.size() - 1;      while (left &lt; right) {         swap(arr[left], arr[right]);  // swap first and last element         left++;         right--;     } }
