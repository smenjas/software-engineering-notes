# Number Theory Tutorial

So if I want to represent the number 3 in base 10 (decimal), it’s: 3.

But if I want to represent the number 3 in base 2 (binary), it’s: 11.

In base 10: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10

In base 2: 1, 10, 11, 100, 101, 110, 111, 1000, 1001, 1010

See?  We are just using 1s and 0s, but we can represent any number.

So, for the decimal (base 10) number 9, we have a 1 in the 8s place, and a 1 in
the 1s place.

8 + 1 = 9

For the decimal (base 10) number 7, we have a 1 in the 4s place, 1 in the 2s
place, and 1 in the 1s place.

4 + 2 + 1 = 7

So the places in decimal (base 10) are: 1, 10, 100, 1000, etc.

The places in binary (base 2) are: 1, 2, 4, 8, 16, 32, 64, 128, 256, 512, 1024,
2048, 4096, …

So the places in decimal (base 10) are: 10^1, 10^2, 10^3, …

The places in binary (base 2) are: 2^1, 2^2, 2^3, 2^4, 2^5, …

So the formula for the value of a place in a number, given a base, is:
```js
base^place = value;
```

This is how numbers work, which mathematicians call “Number Theory”

Now if you are trying to read binary, it’s hard: 10100010101010101001010010101

So sometimes programmers use hexadecimal (base 16).

Each digit of a hexadecimal number may be any of: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9,
A, B, C, D, E, or F.

How many binary digits does one hexadecimal digit represent?

How many binary digits do you need to have 16 different values?

(Those two questions are asking the same thing.)

If you can answer this question, you know number theory.

Hint: the answer to the questions above is the binary (base 2)
[logarithm](https://en.wikipedia.org/wiki/Logarithm) of 16.
