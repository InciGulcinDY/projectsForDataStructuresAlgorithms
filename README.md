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
--------------------------------------------------
# Project 3
# The steps of Binary-Search-Tree [7,5,1,8,3,6,0,9,4,2]
* Step-1: Start with the first element, 7, as the root of the tree.  
Tree:  
7  
* Step-2: Compare the second element, 5, with the root (7) and insert it as the left child since it is smaller.  
Tree:  
7  
/  
5  
* Step-3: Compare the third element, 1, with the root (7) and insert it as the left child of the left subtree since it is smaller than 7 and 5.  
Tree:  
     7  
  /     
 5         
/  
1  
* Step-4: Compare the fourth element, 8, with the root (7) and insert it as the right child since it is greater.  
Tree:  
     7  
  /    \  
 5      8  
/   
1    
* Step-5: Compare the fifth element, 3, with the root (7). Since it is smaller, move to the left child (5). Compare it with 5 and insert it as the left child since it is smaller.  
Tree:  
     7  
  /    \  
 5      8  
/ \  
1  3  
* Step-6: Compare the sixth element, 6, with the root (7). Since it is greater, move to the right child (8). Compare it with 8 and insert it as the left child since it is smaller.  
Tree:  
     7  
  /    \  
 5      8  
/ \    /  
1  3  6  
* Step-7: Compare the seventh element, 0, with the root (7). Since it is smaller, move to the left child (5), then to its left child (1). Compare it with 1 and insert it as the left child since it is smaller.  
Tree:  
         7  
      /    \  
     5      8  
    / \    /  
   1  3  6  
  /  
0    
* Step-8: Compare the eighth element, 9, with the root (7). Since it is greater, move to the right child (8), then insert it as the right child since it is greater.  
Tree:  
         7  
      /    \  
     5      8  
    / \    / \  
   1  3  6    9  
  /  
0   
* Step-9: Compare the ninth element, 4, with the root (7). Since it is smaller, move to the left child (5), then to its right child (3). Compare it with 3 and insert it as the right child since it is greater.  
Tree:  
         7  
      /    \  
     5      8  
    / \    / \  
   1  3  6    9  
  /    \  
0       4  
* Step-10: Compare the tenth element, 2, with the root (7). Since it is smaller, move to the left child (5), then to its left child (1), and finally to its right child (3). Compare it with 3 and insert it as the left child since it is smaller.  
Tree:  
         7  
      /    \  
     5      8  
    / \    / \  
   1  3  6    9  
  / \   \  
0    2   4  


