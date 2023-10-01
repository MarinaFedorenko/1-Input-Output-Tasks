# NIX-Homework-1
**Task 1:** Value Exchange <br>
<em>Input:</em> Enter two integers a and b. <br>
<em>Output:</em> Display the answer to the problem.<br>
The solution to the problem should not be code <ins>like this</ins>:
```java
a = input()
b = input()
print(b, a)
```
In other words, your program should have a structure similar to this:
```java
a = input()
b = input()
# Write your code here
# Your code here
print(a, b)
```
**Task 2:** End of Classes<br>
In a certain school, classes start at 9:00. The duration of a lesson is 45 minutes. After the 1st, 3rd, 5th, and so on lessons, there is a 5-minute break, and after the 2nd, 4th, 6th, and so on lessons, there is a 15-minute break. Determine when the specified lesson ends. <br>

<em>Input:</em> Given the lesson number (a number from 1 to 10). <br>
<em>Output:</em> Output two integers: the time when the lesson ends in hours and minutes. You should solve this problem without using loops or conditional statements. <br>

<ins>Examples: </ins><br>
Input: 3 <br>
Output: 11 35<br>

Input: 2 <br>
Output: 10 35<br>

**Task 3:** Time Difference<br>
You are given values of two moments in time that belong to the same day: hours, minutes, and seconds for each of the moments. It is known that the second moment in time occurred no earlier than the first one. Determine how many seconds have passed between these two moments in time.<br>

<em>Input:</em> The program receives three integers — hours, minutes, and seconds, representing the first moment in time, and three integers representing the second moment in time.<br>
<em>Output:</em> Output the number of seconds between these two moments in time.<br>
<ins>Examples:</ins><br>
Input:
1
1
1
2
2
2<br>
Output: 3661<br>

Input:
1
2
30
1
3
20<br>
Output: 50<br>
Input: 2 <br>
Output: 10 35<br>

**Task 4:** Car Trip<br>
A car travels n kilometers in one day. How many days are needed to cover a route of length m kilometers?
In solving this problem, you cannot use conditional statements (if) or loops.<br>

<em>Input:</em> The program receives two natural numbers, n and m, not exceeding 10,000.<br>
<em>Output:</em> Output the answer to the problem.<br>

<ins>Examples:</ins><br>
Input:
700
750<br>
Output: 2<br>

Input:
700
2100<br>
Output: 3<br>

**Task 5:** Snail<br>
A snail is crawling up a vertical pole with a height of h meters. During the day, it climbs a meters, and at night it descends b meters. On which day will the snail reach the top of the pole?<br>

<em>Input:</em> The program receives three natural numbers, h, a, and b. It is guaranteed that a > b.<br>
<em>Output:</em> The program should output a single natural number.<br>
<ins>Note:</ins> You should solve this problem without using conditional statements (if) or loops.<br>

<ins>Examples:</ins><br>
Input:
10
3
2<br>
Output: 8<br>

Input:<br>
20
7
3<br>
Output: 5<br>

**Task 6:** Maximum<br>
Write a program that reads two integers, a and b, and outputs the greater of the two values. The numbers are integers from 1 to 1000.
In solving this problem, you can only use integer arithmetic operations: +, -, *, //, %, and =. You cannot use non-linear constructs like conditionals, loops, functions to calculate absolute values, or square root extraction.
Using the max function is prohibited!<br>

<em>Input:</em> Two integers, a and b.<br>
<em>Output:</em> Output the answer to the problem.<br>

<ins>Examples:</ins><br>
Input:
8
5<br>
Output: 8<br>

Input:
5
8<br>
Output: 8<br>

Input:
5
5<br>
Output: 5<br>

**Task 7:** Rook<br>
You need to determine whether a rook, standing on the specified square (given by its row and column numbers), can capture a piece standing on another specified square.<br>

<em>Input:</em> Four numbers are entered: the coordinates of the rook (two numbers) and the coordinates of another piece (two numbers). Each number is entered on a separate line. Coordinates are integers in the range from 1 to 8.<br>
<em>Output:</em> Output "YES" if the rook can capture the piece in one move, and "NO" otherwise.<br>

<ins>Examples:</ins><br>
Input:
1
1
2
2<br>
Output: NO<br>

Input:
1
1
2
1<br>
Output: YES<br>

**Task 8:** Number of Equals Among Three<br>

<em>Input:</em> Three integers are given, each on a separate line. Determine how many of them are equal.<br>
<em>Output:</em> The program should output one of the numbers: 3 (if all are equal), 2 (if two are equal), or 0 (if all three numbers are different).<br>

<ins>Example:</ins><br>
Input:
1
2
2<br>
Output: 2<br>

**Task 9:** Count of Elements Greater Than the Previous One<br>

<em>Input:</em> You are given an array consisting of integers. Write a program that counts the number of elements in the array that are greater than the one preceding it.
Input starts with a number N, which is the number of elements in the array (1 ≤ N ≤ 10000). Then, N integers are listed separated by spaces, which are the elements of the array. The array consists of integers.<br>
<em>Output:</em> Output a single number, which is the count of elements in the array that are greater than the one preceding them.<br>

<ins>Example:</ins><br>
Input:<br>
5<br>
1 2 3 4 5<br>
Output: 4<br>

**Task 10:** Count of Elements Greater Than Both Neighbors<br>

<em>Input:</em> You are given an array consisting of integers. Write a program that determines the number of elements in the array that have two neighboring elements, and both of those neighbors are smaller than the element itself.
Input starts with a number N, which is the number of elements in the array (1 ≤ N ≤ 100). Then, N integers are listed separated by spaces, which are the elements of the array. The array consists of integers.<br>
<em>Output:</em> Output the count of elements in the array that have two neighbors and are strictly greater than both of their neighbors.<br>

<ins>Example:</ins><br>
Input:<br>
5<br>
1 2 3 4 5<br>
Output: 0<br>

Input:<br>
5<br>
1 5 1 5 1<br>
Output: 2<br>

**Task 11:** Rearrange Adjacent Elements<br>

<em>Input:</em> Write a program that rearranges adjacent elements of an array (swap the 1st element with the 2nd, the 3rd with the 4th, and so on). If the number of elements is odd, the last element remains in its place.
Input starts with a number N, which is the number of elements in the array (1 ≤ N ≤ 35). Then, N integers are listed separated by spaces, which are the elements of the array. The array consists of integers.<br>
<em>Output:</em> Output the array after rearranging its elements.<br>

<ins>Example:</ins><br>
Input:<br>
6<br>
4 5 3 4 2 3<br>
Output:
5 4 4 3 3 2<br>
