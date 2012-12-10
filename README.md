PGP Algorithm
==========

This is a novice programmer's attempt at implementing the key generating parts of PGP. In many uses of PGP, the Diffie–Hellman algorithm is used so this is what I used.

#Feel Free to use this code anyway you want! It was made purely for learning purposes.

---------------------------------------------------------------------------------------------
General Purpose
---------------------------------------------------------------------------------------------
  The general purpose of this program is to provide a rather elementary representation of how the PGP alogorithm works. This was done as a school assignment.
  
---------------------------------------------------------------------------------------------
How it Works
---------------------------------------------------------------------------------------------
  For the most part, the program is rather self-explanatory. I simulate the half of the PGP algorithm that requires another user while requesting input from the primary user(the person running the program.)
  This implementation does not include Euler's totient function as I could think of an algorithm due to being a novice programmer. Because of this, I use a predetermined prime number and a generator when going going through the PGP steps. However, the program is capable of checking to see if the user entered a prime number. This block of code is commented out as checking the prime number of the user is useless if I can't find a primitive root based on the chosen prime.

---------------------------------------------------------------------------------------------
Background
---------------------------------------------------------------------------------------------
  As I said early, I'm a novice programmer and this is my first real at making a "real" program. As such, the code is probably heavily unoptimized and you may notice that even the syntax is rather inefficient for a beginner level Python user. I have more experience in C# than Python which would explain some of the inefficient syntax. I am still not comfortable with mkaing my own Python function which is why avoided making one even though I knew it would make my program better.
  
  Hopefully things get better from here on out. GG