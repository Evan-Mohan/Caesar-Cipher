# Ceaser-Cipher

Mathematical Analysis

There are only 25 possible keys.

Caesar code replaces a letter with an inverse alphabet shift. It uses substitution, the letters in the alphabet are shifted by some amount of spaces to get an encoding alphabet. For example, a Caesar cipher with a shift of 1 would encode an A as a B, an M as an N, and a Z as an A, and so on.

In an equation it can be described as:

D_n(x)=(x-n)mod\ 26  
(Decryption Phase with shift n, you take the remainder after dividing by 26)


Here is an example where it is shifted by 3:
Normal Alphabet | Caesar Alphabet (Shifted 3)
------------ | -------------
ABCDEFGHIJKLMNOPQRSTUVWXYZ | DEFGHIJKLMNOPQRSTUVWXYZABC

How would you attempt to decode if you didn't have a key: Caesar ciphers are susceptible to brute force attacks, where the person or computer trying to decode tries each possible combination of letters.

## [Hub](README.md)
