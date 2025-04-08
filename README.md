# Python Program: Construct an AVL Tree and Display Its Nodes

## Aim
To construct an AVL (Adelson-Velsky and Landis) tree using the given elements
and print the structure of the AVL tree using a suitable Python package.

## Procedure
1. Use the `binarytree` module, which supports creating custom balanced binary trees.
2. Define an AVL Tree Node class with height tracking.
3. Implement insertion logic with automatic balancing using rotations (LL, RR, LR, RL).
4. Insert the given elements into the AVL tree one by one.
5. Print the tree structure using pre-order or level-order format.

## Python Program
```python
from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print(getDictTree(tree))

L=[12,8,18,5,11,17,4,7,2]
```
# Output:
![image](https://github.com/user-attachments/assets/13351379-cd7d-4e35-bd03-3d31f873963e)

# Result:
Thus The program inserts the values into an AVL tree while maintaining balance and prints it completed successfully.
