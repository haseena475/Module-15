# Ex. No: 15E - Build and Evaluate an Expression Tree

## AIM:
To write a Python program to build and evaluate the given Expression tree.

---

## ALGORITHM:

1. **Start the program.**
2. Create nodes for operators and operands.
3. Build the expression tree by connecting nodes in the correct hierarchical structure.
4. Define a recursive function `evaluate(root)`:
   - If the node is a number (leaf), return it.
   - Else, recursively evaluate left and right subtrees.
   - Apply the operator at the current node to the results.
5. Return the final result from the root node.
6. **End the program.**

---

## PROGRAM:

```
Begin the program.
Import the necessary modules (build, Node) from the binarytree package.
Define a list x representing the binary tree in pre-order format.
Use the build() function to construct the expression tree from the list.
Print the inorder traversal of the expression tree using .inorder.
Print the postorder traversal of the expression tree using .postorder.
End the program.
Program
from binarytree import build
x=['*','+','-',9,3,8,4]
tree=build(x)
print(tree.inorder)
print(tree.postorder)
```

## OUTPUT:
<img width="1149" height="211" alt="image" src="https://github.com/user-attachments/assets/43f6d241-bede-48b2-8ff4-d501f8cd9888" />


## RESULT:

Thus the python program was initialised and executed successfully
