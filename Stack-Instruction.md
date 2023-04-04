# Introduction 
A Stack works like a stack of papers, the last one put on the pile will be the first taken off. 

## They have many benefits such as:
1. They are efficient for Memory Managment. They are sequential just like a stack of papers; The last one is first out.
2. They are simple, they only have two functions. "Push" and "Pop".
3. They are good at performing Recursive Algorithms. such as depth-first.
4. They can reverse order with simplicity. Such as a word list.
5. They are good for undoing Operations. You can keep track of what has been done and undo them in reverse order.

## How to use Stacks.
1. How to add to a stack
    Using append.
    Example: stack.append(1)
             stack.append(2)

2. Print your stack.
    Example: print(stack)
    
3. How to remove your last item from the stack.
    Example: item = stack.pop()
    print(item)
   
4. How to reverese the order of a stack
    Example: stack.reverse()
    
    
    
## Example 
```
# Make a empty stack.
aux_stack = []
    

stack.append('A')
stack.append('B')
stack.append('C')
item = aux_stack.pop()

# will print last letter added 'C'
print(item)

```

## Example problem

Try the following problem. 
Create a stack and load 5 numbers in to it. Then reverse the order of the numbers in the stack.

[Solutions](/Answers/Stack-Answers.md)


