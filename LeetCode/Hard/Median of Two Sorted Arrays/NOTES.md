
          Median of Two Sorted Arrays

          - Summary: The code uses vectors (dynamic arrays) to store and manipulate input and merged arrays. It first merges two sorted input vectors into a single vector. Then, it sorts the merged vector and determines the median based on whether the total number of elements is even or odd. If odd, the middle element is the median; if even, the average of the two middle elements is the median.

          - Time Complexity: O(m+n+k log k), where m and n are the lengths of the input arrays and k = m+n. The merging of arrays takes O(m+n), sorting takes O(k log k), and other operations are O(1).  The dominant factor is the sorting step. If the input arrays are already sorted, the merging step would be O(m+n), and we can avoid the sort, resulting in overall O(m+n).
          - Space Complexity: O(m+n), as a new vector of size m+n is created to store the merged array.  The space used is linear with respect to the total input size.
          