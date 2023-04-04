# Introduction 
A Set works as an unordered collection of elements. But unlike a list they are all unique. Because of this you cannot enter the same data twice. And you cannot put them in order.

##They have many benefits such as:
1. They are unique. This is good if you don't want repeats. It would be like if you had box of random pieces to a puzzle you would not want the same pieces over and over in your puzzle.
2. They are designed for fast membership testing.
3. They are good for mathematical set operations. So, you can compare or combine data.
4. They can do iterable. So, you can loop through fast with a for loop.
5. They are good manipulating data. add(), update(), discard() and so on.

##How to use sets.
1. How to add to a set
    
    Example: the_set = {1, 2, 3, 4, 5}
             the_set.add(6)

2. Print your set.
    Example: print(set)
    
3. How to remove an item from a set.
    Example: the_set.remove(6)
    print(item)
   
4. How to check the difference of different sets.
    Example: the_set.difference()
    set1 = {1, 2, 3, 4, 5}
    set2 = {'pear', 'apple', 'Banana'}
    set3 = set1.difference(set2)

    print(set3)
    
##Example 
```
#Make a set.
the_set = {1, 2, 3, 4, 5}
    

set.update(6)
set.update(7)
set.update(8)
the_set.remove(6)

#will print '1, 2, 3, 4, 5, 7, 8'
print(item)

```

##Example problem

Try the following problem. 

[Solutions](/Answers/Set-Answers.md)

```
#find what is different
set1 = {3, 4, 5, 6, 7}
set2 = {1, 2, 3, 4, 5} 

#Answer = {1, 2, 6, 7}

```
