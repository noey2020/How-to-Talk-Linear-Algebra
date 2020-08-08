# How-to-Talk-Linear-Algebra

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me!

Linear Algebra 101

Linear algebra is one of the mathematics,including Statistics and Probability,
used in data science. Matlab, Python and R are the programming & scripting
languages in popular use, with Matlab preferred in academia because it offers
free academic licenses. Matlab is freeform and is more of scripting rather than
programming so it resembles doing the "math by hand" as compared to programming.
Python is free, open-source and one-line testing of "proof of concept" so it 
finds widespread appeal and more collaboration among peers.

I leave the theoretical details to advanced texts and delve into practical 
problem solving here.

To solve a system of simultaneous linear equations, we use matrix notation and
write it as:

  Ax = b
  
A is a given square matrix of order n, b is a given column vector of n 
components, and x is an unknown column vector of n components. In matrix-vector
form, it becomes:

  [A]x = b
  
The solution to Ax = b can be written: 1) x = b/A and 2) x = A-1b, where A-1 is
the inverse of A.
  
Given that A is a matrix of any size and shape and B is a matrix with as many
rows as A, then the solution to the system of simultaneous equations AX = B is
denoted by

  X = A\B   if left division.
  
Similarly, the solution to a system with A on the right and B with as many
columns as A, XA = B, is obtained by right division,

  X = B/A. 
  
To illustrate with a set of linear equations,
 
  6y = -5x
  
   y = -3x -5
   
We rewrite them in matrix-vector form,

  5x + 6y = 0
  
  3x + 1y = -5,    Remember: [A]x = b.
  
In Matlab,  

  A = [ 5 6; 3 1 ];   % define the A matrix
  
  b = [ 0; -5 ];      % define the b vector
  
  x = A\b;            % solution to the system of linear equations.
  
Using matrix inverse,

  A = [ 5 6; 3 1 ];
  
  b = [ 0; -5 ];
  
  Ainv = A^-1;        % calculate the inverse of A
  
  x = Ainv*b;         % calculate the solution
  
The inverse requires more arithmetic - a division and a multiplication instead of
just a division - and produces a less accurate answer.

I included some posts for reference.

https://github.com/noey2020/How-to-Make-Predictions-in-Python

https://github.com/noey2020/How-to-Talk-Hashing

https://github.com/noey2020/How-to-Talk-Algorithm-Analysis

https://github.com/noey2020/How-to-Talk-Recursion

https://github.com/noey2020/How-to-Talk-Linked-Lists

https://github.com/noey2020/How-to-Talk-Queues

https://github.com/noey2020/How-to-Talk-Stacks

https://github.com/noey2020/How-to-Talk-Lists-Stacks-and-Queues

https://github.com/noey2020/How-to-Talk-Linear-Regression

https://github.com/noey2020/How-to-Talk-Statistics-Pattern-Recognition-101

https://github.com/noey2020/How-to-Write-SPI-STM32

https://github.com/noey2020/How-to-Write-SysTick-Handler-for-STM32

https://github.com/noey2020/How-to-Write-Subroutines-in-C-Assembly-STM32

https://github.com/noey2020/How-to-Write-Multitasking-STM32

https://github.com/noey2020/How-to-Generate-Triangular-Wave-STM32-DAC

https://github.com/noey2020/How-to-Generate-Sine-Table-LUT

https://github.com/noey2020/How-to-Illustrate-Multiple-Exceptions-

https://github.com/noey2020/How-to-Blink-LED-using-Standard-Peripheral-Library

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me!

Have fun and happy coding!


