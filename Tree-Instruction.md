A Tree works like a family tree. You have parents in the family and children of those parents, and you can look up children by looking up parents. 

##They have many benefits such as:
1. They are efficient at retrieving specific data, elements, or other information.
2. They are flexible. Able to make structures such as hierarchical data and nested structures.
3. They are easy to implement by using classes or objects.
4. They are memory efficient as they only need markers to the nodes and pointers to the children.
5. They are good for keeping sorted order and fast intersection of detection while keeping the order the same.


##How to use a tree.
1. Define a 'Node' this is a class that will represent every 'Node' in the tree.
every node will have a 'right' and 'left' and a 'data' to hold the value of the node.
example:
class Node:
```
    def __init__(self, data,):
        self.data = data
        self.left = none
        self.right = none
```
2. You must define a 'BinaryTree' class. This will represent the tree itself. 
You will also need a 'root' that will hold the root node as well as an 'add_node' to add a new node to the tree.

3. Create another instance of the 'BinaryTree' class.

4. You can now add node using the 'add_node' method.

5. You can retrieve data from the nodes in the tree. (print or return values.)
    
    
    
    
##Example 
```
1. Make a tree and children
    tree = {
        'item':1 apple,
        'child':{
            'item':2 apple,
            'child': [
                {'item': 4 pear, 'child': []},
                {'item': 5 pear, 'child': []}
            ]
        }'
        {
            'item': 3,
            'child': []
        }
    }

2. Print your tree.
    Example: print(tree)


```

##Example problem

Try the following problem. 
Finish a tree with trivia questions and true/false answers.

```
class T_Node:
    def __init__(self, data, right=None, left=None):
        self.data = data
        self.left = left
        self.right = right

    def is_leaf(self):
        # TODO Evaluate if the statement is true or false (based on the tree) and return a corrsponding response


data = T_Node('An animal can lay eggs and still be a mammal.', T_Node('The tallest land animal is not the biggest animal.'))
play(data)

```

[Solutions](/Answers/Tree-Answers.md)
