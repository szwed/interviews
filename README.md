# Interviews

## Programming

### Generic Questions

1. Which approach is better: Multiple threads or multiple processes? Why? When?
1. Which approach is safer from the hardware failure point of view?
  - 4x processes 
  - 1x process with 4 threads 

1. When we should use Binary Trees?
1. Can you enumerate and explain the various types of errors that can occur during the execution of a computer program?
1. What do you understand by LIFO and FIFO?

### Python

#### Questions

1. What is the difference between list and tuples in Python?
1. What type of language is python? Programming or scripting?
1. What is the difference between .py and .pyc files?
1. Mention the differences between Django, Pyramid and Flask.
1. Is python numpy better than lists? Why?
1. What does `[::-1}` do?
1. How memory management is done in Python?
1. How do you debug a Python program?
1. What is `__init__()` in Python?

#### Coding

1. Write a sorting algorithm for a numerical dataset in Python.
1. Write a one-liner that will count the number of capital letters in a file. Your code should work even if the file is too big to fit in memory.
1. Looking at the below code, write down the final values of A0, A1, …An.
```
A0 = dict(zip(('a','b','c','d','e'),(1,2,3,4,5)))
A1 = range(10)A2 = sorted([i for i in A1 if i in A0])
A3 = sorted([A0[s] for s in A0])
A4 = [i for i in A1 if i in A3]
A5 = {i:i*i for i in A1}
A6 = [[i,i*i] for i in A1]


A0 = ?
A1 = ?
A2 = ?
A3 = ?
A4 = ?
A5 = ?
A6 = ?
```
