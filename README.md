# Binary Tree Package

This Python script defines a `Binary_Tree` class that includes methods for creating and managing a binary tree. The tree is implemented using a linked structure with nodes and pointers.

## Prerequisites

Make sure you have the following Python files in the same directory as the script:

- `pointer.py`: Contains the `Pointer` class.
- `node.py`: Contains the `Node` class.

## Usage

1. Import the necessary classes from the required files:

    ```python
    from pointer import Pointer
    from node import Node
    ```

2. Create an instance of the `Binary_Tree` class:

    ```python
    tree_values = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    my_tree = Binary_Tree()
    ```

3. Use the `bst` method to create a binary search tree:

    ```python
    my_tree.bst(tree_values)
    ```

## Methods

### `bst(self, values)`

Creates a binary search tree (BST) using the provided values. The method initializes the tree with the first value and inserts subsequent values based on the rules of a binary search tree.

## Example

```python
from pointer import Pointer
from node import Node

tree_values = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
my_tree = Binary_Tree()
my_tree.bst(tree_values)
```

## Note

- Ensure that the `pointer.py` and `node.py` files are present in the same directory as the script.
- The current implementation assumes a non-empty list of values for tree construction.
