# Mixed-Numbers

Mixed Numbers

Description

A mixed fraction is defined recursively as follows: 

A real value is a simple mixed fraction. For simplicity, we only consider one digit positive integer numbers greater than zero (digits 1 ... 9). 
If a is a real value (which is again assumed as an integer between 1 and 9), and b and c are two mixed fractions, 
 b

a- is a mixed fraction which is equal to a + b/c

 c

Sum of a number of mixed fractions is also a mixed fraction. 

One can draw a view of a mixed fraction using ASCII characters as described below: 

A simple mixed fraction can be drawn using one digit character. 
                     b

The mixed fraction  a-  will be drawn using a digit showing  a , and a horizontal line that starts 

                     c

immediately after the letter representing a (in the same row) using '-' characters. b and c are drawn recursively above and below the horizontal line respectively, such that their figures do not exceed the line from left nor right. 
Sum of mixed fractions is represented by drawing the mixed fractions and inserting a '+' character between each consequence pair such that the '+' character and the first character of the next and the previous mixed fractions make a horizontal line. 

We want you to write a program to calculate the value of a mixed fraction from its figure.

Input

Some 90 degree clockwise rotated figures of a number of mixed fractions are given in the input file. In the first line of each rotated mixed fraction n < 300 and m < 15000 , the length and the width of the figure, are written. In the next m lines the figure i s described ('-' is replaced with '|'). Note that each line will consists of exactly n characters so any number of spaces may be used in the shape, but anyway, the shape of the figure satisfies description explained above. 
The input ends with a line containing two zeroes.

Output

For each test case write its value in a separate line. Your answer must be rounded to two digits after decimal point and the output must contain exactly two digits after the decimal point.

Sample Input

8 6
   1    
 2 |  2 
4|2| 4|3
   |    
   +    
   1    
0 0
Sample Output

3.10
