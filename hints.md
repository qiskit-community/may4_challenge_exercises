# Hints for completing the IBM Quantum Challenge

Welcome to the IBM Quantum Challenge! This document outlines some learning material and hints that you might find useful as you solve the exercises in the Challenge. 

### Asking questions and communicating with other participants
- To ask questions about the challenge and communicate with other participants, please [join our Qiskit Slack community](https://join.slack.com/t/qiskit/shared_invite/enQtODQ2NTIyOTgwMTQ3LTI0NzM2NzkzZjJhNDgzZjY5MTQzNDY3MGNiZGQzNTNkZTE4Nzg1MjMwMmFjY2UwZTgyNDlmYWQwYmZjMjE1ZTM) and share your thoughts on the channel [#ibm-quantum-challenge](https://qiskit.slack.com/archives/C0137AVM396). In this channel, you will find other participants to collaborate with, and you will also be able to ask questions directly to our scientists who created the challenge.

## Hints for Exercise 1

Quantum computing is a new and exciting field, and we are all learning together.

- Is this your first time digging into quantum computing? Watch this video: https://qisk.it/quantum5levels


- If you don't have experience with Python and Jupyter notebooks, please read this quick introduction in the Qiskit textbook: https://qisk.it/pythonprereqs


- You will be using the open source software development framework called Qiskit to solve the exercises in the IBM Quantum Challenge. Qiskit is primarily written in Python. If you already have some familiarity with quantum computing, but not with programming quantum computers using Qiskit, then

    - read this quick introduction to Qiskit in the Qiskit textbook: https://qisk.it/qiskitprereqs
    
    - watch this video to write your first Hello World application in Qiskit: https://qisk.it/helloworld


## Hints for Exercise 2

Measurement error mitigation is a very useful technique for obtaining the best performance from today's quantum computers. We have described the technique in this video: https://qisk.it/measerrormitigation


## Hints for Exercise 3

This exercise requires looping through bitstrings and doing comparisons. In Python, a loop that goes through a string called `str_example` from left to right is shown below.

```python
str_example = 'Hello World!'
for letter in str_example:
    print(letter)
    if letter == 'H':
        print("I found an H!")
```
The output of the above code is

```python
H
I found an H!
e
l
l
o

W
o
r
l
d
!
```

If you want to reverse a string, here is an example.

```python
str_example = 'Hello World!'
str_example_reversed = str_example[::-1]
print(str_example)
print(str_example_reversed)
```
The output of the above code is
```
Hello World!
!dlroW olleH
```

If you want to go through a string using indices, you can follow the example below. This example takes every second letter in `str_example` and puts it into a new string called `str_final`.

```python
str_example = 'Hello World!'

str_final = ''
for i in range(len(str_example)):
    if i % 2 == 0:
        str_final += str_example[i]
        
print(str_example)
print(str_final)

```
The output of the above code is

```python
Hello World!
HloWrd
```

## Hints for Exercise 4

In this exercise, you will be finding the quantum circuit that results in a unitary transformation described by a given matrix. You might find it useful to look at Qiskit's `transpile` tool, and the various optimization levels within that tool.