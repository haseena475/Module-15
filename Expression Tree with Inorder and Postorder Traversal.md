# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
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

## OUTPUT
<img width="1149" height="211" alt="image" src="https://github.com/user-attachments/assets/34e17ef1-bdb7-4607-afa1-60793d74a3c4" />

## RESULT

Thus the python program was initialised and executed successfully.
