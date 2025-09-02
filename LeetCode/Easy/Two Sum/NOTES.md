
          Two Sum

          - Summary: This algorithm utilizes an unordered map (hash table) to efficiently find pairs of numbers that sum to a target value.  It first populates the hash table with each number in the input array and its index. Then, it iterates through the array again; for each number, it checks if the complement (target - number) exists in the hash table. If the complement is found and its index differs from the current number's index, it returns the indices of the pair. Otherwise, it continues until a pair is found or the array is exhausted.

          - Time Complexity: O(n) because the algorithm involves two iterations through the input array of size n. Hash table operations (insertion and lookup) take constant time on average.
          - Space Complexity: O(n) because the space used by the unordered map is proportional to the number of elements in the input array.
          