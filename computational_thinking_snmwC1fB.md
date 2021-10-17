# Computational Thinking

Loose formal definition:

•Computer science is the study of the theory and methods of processing information/data in computer systems

•Theory of computation

*   Encompasses many distinct subfields

•Artificial Intelligence

•Computer architecture

•Programming language theory

•Many, many more

  

* * *

  

  

  

*   Computer Science and Computer Programming are different

•Computer programming is the art, science, and process of developing programs

*   Computer programming is an application of computer science

  

*   Computational Thinking is a way of understanding complex problems to develop possible solutions

  

*   it also includes using that understanding to present solutions in a way that both people and computers can understand

  

*   It is made up of 4 parts: (Decomposition, Pattern Recognition, Abstraction, and Algorithms

  

*   Decomposition - Breaking down a problem into smaller and more manageable problems

  

*   Involves finding steps that we can repeat

  

*   Pattern recognition - recognizing similar problems and how they have been solved before.

  

*   As problems are often about processing or manipulating data, also recognizing patterns in the data that can be used to create a solution. Sometime this is called parsing

  

*   Presenting solutions that show patterns and trends – part of recognizing a pattern is also being able to present it to others

  

*   Abstraction - being able to discern the important parts of a problem from the irrelevant ones, and using those important parts to make your solution

  

*   Making generalized solutions based on patterns found – creating models and rules that describe patterns found

  

*   Example: equations that govern motion (position, speed, acceleration, etc.)

  

*   Makes things easier for humans to understand and use

* * *

Algorithms
==========

  

*   Developing step-wise, precise steps to solve a problem
*   Often involves creating algorithms for the smaller parts of a problem as well
*   Think of this as a recipe, described in words
*   Coding/Programming is turning the recipe into something a computer can execute for us

  

*   An algorithm is a precise, unambiguous, finite sequence of steps for completing a given task or solving a given problem.
*   Key words:

•precise

*   Every step is described
*   unambiguous
*   After each step, there is a unique next step
*   finite
*   At some point, there are no more steps and a solution is generated (or it is clear there is no solution)
*   Example: Euclid’s algorithm for finding the greatest common divisor of two integers:

```
Given any two integers a, b
if b = 0, result is a
otherwise
•t = b
•b = a mod b
•a = t
repeat
```

*   Precise

•At any step in the process, we know what to do next

*   Unambiguous

•There is never more than one possible next step

*   Finite

We will always finish, no matter what

Non example:

```
open sock drawer
pick up two socks
if the socks match, put them on
otherwise, put both socks back and try again


```

*   _Why is this not an algorithm?_
*   Not precise – what do we do if there aren’t two socks?
*   Not unambiguous – what does “try again” mean?
*   Not finite – we might never finish!

Putting on socks (Fixed Version)

```
open sock drawer
while there are socks left in the drawer
pick up a sock
while there are socks left in the drawer
pick up another sock
if the two socks match, put them on
otherwise, put the second sock aside in a pile
repeat
when there are no more socks, return all socks in the pile to the drawer
put the first sock aside in a basket
repeat
when there are no more socks, give up


```

*   Computers do exactly what they’re told and only what they’re told

•The computer does not make mistakes

*   In order to effectively write programs, we must learn to think like a computer
*   This is writing or developing an algorithm
*   “Programming” is translating the algorithm into a language the computer can understand