# Trees
BT Problem Solving - Code Story WithMIK Series

Along with GFG series- https://www.geeksforgeeks.org/explore?page=9&category=Tree,Binary%20Search%20Tree&sortBy=submissions



https://leetcode.com/problems/pseudo-palindromic-paths-in-a-binary-tree/

https://leetcode.com/discuss/post/1337373/tree-question-pattern-2021-placement-by-t65qm/


Intresting Problem : The questions can be asked in reverse:  
https://leetcode.com/problems/construct-string-from-binary-tree/description/  

Given This string we may be asked to find the depth of the tree.    

Each () represent a level , so we basically need to calcuate the depth.  





Traversals Given	        Can Build Unique Tree?	          Reason
Inorder + Preorder	         ✅ Yes	                 Preorder root + inorder splits subtree
Inorder + Postorder          ✅ Yes	                 Postorder root + inorder splits subtree
Preorder + Postorder	       ❌ No	                 Multiple trees possible
