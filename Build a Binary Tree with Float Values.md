# Ex. No: 15A - Build a Binary Tree with Float Values

## AIM:
To write a Python program to build a binary tree with a root, left, and right node using floating-point values.

---

## ALGORITHM:

1. **Start the program.**
2. **Import** the `Node` class from the `binarytree` module.
3. **Create a root node** using the `Node` class and assign a floating-point value.
4. **Create left and right child nodes** for the root with float values.
5. **Convert the tree** to a list and print the list of nodes.
6. **End the program.**

---

## PYTHON PROGRAM

```
Start the program.
Import the Node class from the binarytree module.
Create a root node using the Node class and input a floating-point value for the root.
Create left and right child nodes for the root using floating-point values.
Convert the binary tree to a list.
Print the list of nodes.
End the program.
Program
from  binarytree import build
l=[]
for i in range(3):
    a=float(input())
    l.append(a)
root=build(l)
print("List of nodes :",list(root))

```

## OUTPUT

<img width="1127" height="214" alt="image" src="https://github.com/user-attachments/assets/36b2588b-f62f-4ab0-b392-64d1e95bd173" />



## RESULT
Thus the python program is initialised and executed successfully.
