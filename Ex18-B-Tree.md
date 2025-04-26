# Ex4(c) B-Tree
## DATE:07.04.2025
## AIM:
To write a C function to delete an element in a B Tree.
## Algorithm
1.	Start
2.	Try to delete the item from the node using delValFromNode. If not found, print "Not present" and return.
3.	If the node's count is 0 after deletion, set tmp to the current node and update myNode to its first linker child.
4.	Free the tmp node.
5.	Update the global root to the new myNode.
6.	Return after deletion.
7.	End
 

## Program:
```
/*
Program to write a C function to delete an element in a B Tree
Developed by: RAGAVI K
RegisterNumber:  212223040161
*/
1.	Start
2.	Try to delete the item from the node using delValFromNode. If not found, print "Not present" and return.
3.	If the node's count is 0 after deletion, set tmp to the current node and update myNode to its first linker child.
4.	Free the tmp node.
5.	Update the global root to the new myNode.
6.	Return after deletion.
7.	End

```

## Output:

![Uploading image.png…]()


## Result:
Thus, the C function to delete an element in a B Tree is implemented successfully.
