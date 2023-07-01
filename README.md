# projectsForDataStructuresAlgorithms
Data structures and algorithms(Kodluyoruz-Frontend101 Training)
# Project 1
# The steps of Insertion Sort [22,27,16,2,18,6]
* Step-1: [22] [27,16,2,18,6]
* Step-2: [22,27] [16,2,18,6]
* Step-3: [16,22,27] [2,18,6]
* Step-4: [2,16,22,27] [18,6]
* Step-5: [2,16,18,22,27] [6]
* Step-6: [2,6,16,18,22,27]
  
# Time complexity: 2(n) + 3 = 2(6) + 3 = 15
* Best Case: O(n) =O(6)
* Average-Worst Case: O(n^2) = O(6^2)

# In this case if the searched data is 18;
* Best Case:  O(1)
* Average-Worst Case: O(n) = O(6)

# The steps of Selection Sort [7,3,5,8,2,9,4,15,6]
* Step-1: [2] [7,3,5,8,9,4,15,6]
* Step-2: [2,3] [7,5,8,9,4,15,6]
* Step-3: [2,3,4] [7,5,8,9,15,6]
* Step-4: [2,3,4,5] [7,8,9,15,6]
* Step-5: [2,3,4,5,6] [7,8,9,15]
* Step-6: [2,3,4,5,6,7] [8,9,15]
* Step-7: [2,3,4,5,6,7,8] [9,15]
* Step-8: [2,3,4,5,6,7,8,9] [15]
* Step-9: [2,3,4,5,6,7,8,9,15]
  
# Time complexity: 
* Best-Average-Worst Case: O(n^2) = O(9^2)
--------------------------------------------------
# Project 2
# The steps of Merge Sort [16,21,11,8,12,22]
* Step-1: [16,21,11] [8,12,22]
* Step-2: [16] [21,11] [8] [12,22]
* Step-3: [16] [11,21] [8] [12,22]
* Step-4: [11,16,21] [8,12,22]
* Step-5: [8,11,12,16,21,22]

# Time complexity: 
* Best-Average-Worst Case: O(n log n) = O(6 log 6)
