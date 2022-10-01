### Question 1:

```
def sum(n):
   if n == 1:
       return 0
   return n + sum(n-1)

a = sum(5)
print(a)
```
What will be the output of the recursive code above?\
Answer: **14**

### Question 2:

Statement A: A function in Python only executes when called.\
Statement B: Functions in Python always returns a value.\
Answer: **A is True but B is False**

### Question 3:

```
some = ["aaa", "bbb"]

#1
def aa(some):
   return

#2
def aa(some, 5):
   return

#3
def aa():
   return

#4
def aa():
   return "aaa"
```
Answer: **1,3,4**

### Question 4:

For the following code:
```
numbers = [15, 30, 47, 82, 95]
def lesser(numbers):
   return numbers < 50

small = list(filter(lesser, numbers))
print(small)
```
If you modify the code above and change filter() function to map() function, what will be the list elements in the output that were not there earlier?\
Answer: **None of the other options**
