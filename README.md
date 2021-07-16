# Js-Training
Basic to advance JS training for beginners.<br />
Link to book: https://basitk41.github.io/Js-Training/index.html
# Basic git commands:
=> git clone repo-path  —> cloning repo locally<br />
=> git branch  —> checking branches and current branch<br />
=> git fetch  —> will fetch new created branches on master<br />
=> git checkout -b branch-name  —> will create new branch and switch to that branch<br />
=> git checkout branch-name  —> will switch to existing branch<br />
=> git pull  —> will pull the code on branch to local<br />
=> git add .  —> will add all uncommitted files and make ready for commit<br />
=> git status  —> see the added files in which you made changes<br />
=> git commit -m “commit” —> commits<br />
=> git push origin HEAD  —>if you created new branch locally, it will create new branch on master with name you created on local and push all code to that.else will push to existing branch.<br />
# Instruction:
=> clone the repo<br />
=> make branch with your own name<br />
=> do the tasks one by one, if any problem, any question, any suggestion, most welcome every time.<br />
=> at the end of this course you will have your own javascript self written book with all examples and exercises solved by self.<br />
=> you will need to write a short definition of each topic and then solve examples for that topic.<br />
# Javascript Course outline:
# Chapter 1:
1)What is Javascript?<br />
2)Setting development environment(node + vscode + live server).<br />
3)case-sensitive(let a, let A).<br />
4)Identifiers,Statements(Start with character,camel Notation,_$,0-9),(ends with ;).<br />
5)printing Hello world.(console.log + alert + write + getElementById/Tag) (browser, node).<br />
6)Comments(// ,/**/).<br />
7)veriables(var + let + const).<br />
8)datatypes(number(.NaN. ), string,boolean,null,undefinded, (array,function,object)=>object ) (typeof).<br />
9)primitives(value type) vs non-primitives(reference type).<br />
10)Expressions(2*2,2+2).<br />
11)Keywords & Reserved words<br />
# Chapter 2:
Variables:<br />
1)Variables declaration(var ,let,const ,let a; ).<br />
2)undefined vs undeclared variables(console.log(a),console.log(b)).<br />
3)Global vs Local variables<br />
4)variable shadowing(global/local with same name).<br />
5)accessing global variable in as local(a=1;{a=2;print(a)}).<br />
6)Non-strict mode(f{a=1;print(a)} print(a)).<br />
7)Strict mode(“use strict”; ).<br />
8)variable hoisting(two phases=>parsing, executing)(print(a);let a;)=(let a; print(a);),(print(a);let a=1;)=(let a;print(a);a=1;) => while parsing variable declaration goes to top.<br />
9)Using let and const keywords (let a;{let b=a;} print(b);=>referenceError),(const pi=3.14;pi=2;=>typeError).<br />
# Chapter 3:
Datatypes:<br />
1)Primitive: string, number,boolean,null,undefined,symbol=>ES6.<br />
2)Reference/Non-primitive:complex datatype => object<br />
3)dynamic/loosly couple language => let a=1;a=true;a=‘Ali’<br />
4)number, string,boolean<br />
5)undefined => let a;print(a) => undefined type undefined.<br />
6)null => let obj =null; typeof obj => object.<br />
7)null==undefined.<br />
8)Numbers: integer ,floating , whole=2.0=>2<br />
9)NaN: let a=‘a’;a/2;<br />
10)Strings: ‘Ali’ , “Ali” , “it’s okay” , ‘it’s okay’ , ‘it\’ okay’ ,(immutable) let str=‘Ali’; str = str+’ Khan’ (destroying old two, creating new assigning new);<br />
11)Boolean: let inProgress = true;let completed= false; typeof <br />
12)Boolean function: Boolean(‘Hi’)=>true;Boolean(‘’)=>false;  Boolean(20)=>true;Boolean(0)=>false; Boolean({name:’Ali’})=>true; Boolean(null)=>false;<br />
13)Symbol: symbol type<br />
14)Object: let obj={} , let person={name:’Ali’,age:22}<br />
15)object inside object: person={name:’Ali’,age:22,address:{house:10,street:20}}<br />
16)Accessing object properties: dot . Brackets [] =>person.name/person[‘name’]<br />
17)new keyword: create new Object => let person2 = new person; person2.name = ‘Khan’;<br />
18)Array: <br />
19)Function: hi(name) perform a task , return type calculation. <br />
Summary:6 primitive types:number, string,boolean,null,undefined and symbol<br />
1 complex type/non-primitive type: object.<br />
# Chapter 4:
Operators:<br />
1)Arithmetic => +,-,*,/<br />
2)Assignment => = , += ,-= ,*= ,/= ,%= <br />
3)unary => a=+a / ’10’ => 10, a=-a / ’10’ => -10, a=true => a=+a =>1<br />
4)prefix/postfix increment ++ ,decrement --<br />
5)difference between ++a & a++ => a=10;b=20; c= a— + b; , c=—a +b;<br />
6)Comparison => < ,>, <=, >= ,== , != , strict => === ,!==<br />
7)ternary => a>b?’hi’:’bye’;<br />
8)Logical => ! => a=null,undefined,!20,!0,false,true / !! , || , &&<br />
9)truthy falsy => false || true , false || ‘Ali’<br />
10)Precedence => 2+3*4<br />
# Chapter 5:
Control Flow:
1)if else | ternary ?<br />
2)switch case<br />
3)for<br />
4)while<br />
5)do while<br />
6)infinite loops => //i++ in while loop<br />
7)for in<br />
8)for of<br />
9)break; continue;<br />
# Chapter 6:
Objects:<br />
1)Object Properties<br />
2)Object Methods<br />
3)User-Defined Objects<br /> 
4)Defining Methods for an Object<br />
5)The ’this’ Keyword<br />
6)spread operator<br />
# Chapter 7:
Functions:<br />
1)definition<br />
2)calling<br />
3)parameters<br />
4)rest operator<br />
5)default value<br />
6)hoisting => <br />
declaration: <br />
function foo() {}<br />
Expression:<br />
let bar = function() {}<br />
7)Arrow functions<br />
8)Generator functions<br />
# Chapter 8:
Arrays:<br />
1)Array Properties<br />
2)length<br />
3)Array Methods<br />
4)concat ()<br />
5)every ()<br />
6)filter ()<br />
7)forEach ()<br />
8)indexOf ()<br />
9)join ()<br />
10)lastIndexOf ()<br />
11)map () <br />
12)pop ()<br />
13)push ()<br />
14)reduce () <br />
15)reduceRight ()<br />
16)reverse () <br />
17)shift ()<br />
18)slice ()<br />
19)some ()<br />
20)sort ()<br />
21)splice () <br />
22)toString ()<br />
23)unshift () <br />
24)spread operator<br />
# Chapter 9:
Strings:<br />
1)String Properties<br />
2)Length<br />
3)String Methods<br />
4)charAt()<br />
5)charCodeAt ()<br />
6)contact () <br />
7)indexOf ()<br />
8)lastIndexOf () <br />
9)localeCompare ()<br />
10)match ()<br />
11)replace ()<br />
12)Search ()<br />
13)slice ()<br />
14)split ()<br />
15)substr ()<br />
16)substring ()<br />
17)toLocaleLowerCase()<br />
18)toLocaleUppereCase ()<br /> 
19)toLowerCase ()<br />
20)toString ()<br />
21)toUpperCase () <br />
22)valueOf ()<br />
23)anchor()<br />
24)big()<br />
25)blink ()<br />
26)bold ()<br />
27)fixed ()<br />
28)fontColor () <br />
29)fontsize ()<br />
30)italics () <br />
31)link ()<br />
32)small ()<br />
33)strike ()<br />
34)sub()<br />
35)sup ()<br />
# Chapter 10:
Math:<br />
1)abs ()<br />
2)acos () <br />
3)asin ( ) <br />
4)atan ( ) <br />
5)atan2 ( ) <br />
6)ceil ( ) <br />
7)cos ( ) <br />
8)exp ( )<br />
9)floor ( )<br />
10)log ( )<br />
11)max ( )<br />
12)min ( ) <br />
13)pow ( )<br />
14)random ( )<br />
15)round ( )<br />
16)sin ( )<br />
17)sqrt ( )<br />
18)tan ( ) <br />
# Chapter 11:
Dates:<br />
1)Date()<br />
2)getDate()<br />
3)getDay() <br />
4)getFullYear()<br />
5)getHours()<br />
6)getMilliseconds() <br />
7)getMinutes ()<br />
8)getMonth ()<br />
9)getSeconds ()<br />
10)getTime ()<br />
11)getTimezoneOffset ()<br />
12)getUTCDate ()<br />
13)getUTCDay ()<br />
14)getUTCFullYear ()<br />
15)getUTCHours () <br />
16)getUTCMilliseconds ()<br />
17)getUTCMinutes ()<br />
18)getUTCMonth ()<br />
19)getUTCSeconds () <br />
20)getYear () <br />
21)setDate ()<br />
22)setFullYear ()<br />
23)setHours ()<br />
24)setMilliseconds ()<br />
25)setMinutes () <br />
26)setMonth ()<br />
27)setSeconds ()<br />
28)setTime ()<br />
# Chapter 12:
Numbers:<br />
1)Number Methods<br />
2)toExponential ()<br />
3)toFixed ()<br />
4)toLocaleString ()<br />
5)toPrecision ()<br />
6)toString ()<br />
7)valueOf ()<br />
8)parseInt()<br />
# Chapter 13:
Destructuring:<br />
Object: <br />
let obj = {<br />
Name:”ali”,<br />
Age:22<br />
}<br />
Let {Name,Age} = obj;<br />
Array:<br />
Let arr = [1,2];<br />
Let [first,second] = arr<br />
Swapping:<br />
Let a=1,b=2;<br />
[b,a]=[a,b];<br />
# Chapter 14:
Classes
# Chapter 15:
Promises <br />
Callbacks <br />
Async/Await <br />
# Exercises:
# Exercise 1
Swapping variable's values:</br>
let a=10;</br>
let b=20;</br>
Using only one variable like c</br>
Output should look like: </br>
console.log(a); // => 20 </br>
console.log(b); // => 10 </br>
# Exercise 2
Calculate the area and circumference of a circle where radius is equal to 10.</br>
let r = 10; </br>
Output should look like: </br>
Print a label before each result i.e area of circle , circumference of circle </br>
console.log(circleCircum); // => 62.8 </br>
console.log(circleArea); // => 314 </br>
# Exercise 2.1
Write program for Pythagoras Theorem using Math().</br>
Find the Value of hypotenuse</br>
# Exercise 2.2
Write program for Einstein's Theory of Relativity using Math().</br>
Find the Value of Energy</br>
i.e E=mc^2</br>
# Exercise 2.3
Calculate Mass of earth using Math().</br>
# Exercise 2.4
Write program to find (a+b)^2 using Math().</br>
# Exercise 2.5
Write program to find (a+b)(a-b) using Math().</br>
# Exercise 3
Write a function that takes two numbers and return the maximum of the two.
# Exercise 4
Write function isLandscape(width,height) which take width and height, return true if Landscape else false.
# Exercise 5
fizzbuzz algorithm: </br>
write a function fizzbuzz(input), which take an input, if the number is divisable by 3 return string 'fizz',</br>
if the number is divisable by 5 return string 'buzz', if divisable by both 3 and 5 then return string 'fizzbuzz',</br>
if input is not a number return string 'Not a number'.</br>
Finally if input is number but not divisable by both simply return that number.
# Exercise 6
I want you to implement this function, checkSpeed(speed), this function takes a parameter that's the speed of a car.
Now in this program, I'm assuming that speed limit is 70 km an hour. So if a car is driving under the speed limit, we get this Ok message on the console. Similarly if we pass 70 here, so if somebody is driving exactly at the speed limit, we're still good. We still get the Ok message. Now for every five kilometers above the speed limit, they're going to get 1 point. So if I drive at 75 km an hour, I get 1 point here. But what if I drive at 72 km an hour? I'm still good. So for every 5 km, above the speed limit, we should give the driver 1 point. Now as part of calculating the point here, you will have to use one of the built in
 functions in JavaScript that is Math.floor. We can give this function a floating point number, like 1.3, let's say 1.3 points, and this will convert that to the greatest integer, for example if we go to the console here, and type math.floor of 1.3, we get 1. So you will have to use this function as part of your calculations okay, now here is a tip for you. Back to our checkSpeed function, what if you passed 80 here? We should get 2 points right? So we get 2 points, beautiful. Now what if we drive at 180 km an hour? Our license is suspended. So if a driver gets more than 12 points, then their license should be suspended.

# Exercise 7
 I want you to write a function called showNumbers(limit) that takes a parameter called limit. So we pass a number here, like 10, and when we call this function, we should call all the numbers from 0 to the number we supplied as the limit. Now next to each number if that number is even we should display the even number, otherwise we should display odd.
# Exercise 8
I want you to create a function called countTruthy(array) which takes an array and returns a number of truthy elements in this array. Now what are these truthy or false values, We studied about it earlier.
# Exercise 9
Here is another simple but great exercise, your job is to create a function called show properties. We pass an object here. And this function should display all the properties of this object that are of type string.
# Exercise 10
Here's another simple but great exercise that trains your programming brain. So I want you to create this function called sum(limit), we give it a limit and this function will return the sum of all the multiples of 3 and 5 from 0 up to this limit. Here's an example. What are the multiples of 3 and 5, between 0 and 10. Well, multiples of 3, are 3, 6, and 9 and multiples of 5 are 5 and 10, so I'm including this number that is passed as a limit. Now if you add these numbers together, the result will be 33, and that is the trouble of this function
# Exercise 11
we want to calculate the grade of a student. So here, are the marks of a student in different subjects, let marks=[80,80,50], we pass this array with this function, calculateGrade(marks), what this function does, is first it calculates the average grade. So what is the average here, 80 plus 80 plus 50, that comes to 210 divided by 3, so the average is 70. Now here we need a table to see what grade this average corresponds to. So if the average comes down to this range 1 to 59, the grade should be F, if it is between 60 and 69, that should be D, if it's between 70 and 79, that should be a C. If it's between 8- and 89, that should be a B. And finally if it's between 90 and 100, that should be an A
# Exercise 12
This exercise is a very popular exercise for junior programmers. </br>
use loops to print like that below output:</br>
First Task:</br>

*</br>
**</br>
***</br>
****</br>
*****</br>
Second Task:</br>
*****</br>
 ****</br>
  ***</br>
   **</br>
    *</br>
    
# Exercise 13
I want you to create this function, showPrimes(limit), that takes a limit, and shows all the prime numbers up to this limit. So here are the prime numbers that we have, up to 20, we got 2, 3, 5, 7 and so on.

# Exercise 14
I want you to write a logic which shows us the desired output for a given array.<br>
Example below show a sample output.<br>
const arr = [1, 1, 2, 3, 5];<br>
output =><br>
A - 1<br>
A - 1<br>
B - 2<br>
A - 3<br>
B - 5<br>
if the number change the letter also change.<br>
Here is your task<br>
const arr = [1, 2, 2, 3, 4, 6, 6];<br>
your output should be like below<br>
output =><br>
A - 1<br>
B - 2<br>
B - 2<br>
A - 3<br>
B - 4<br>
A - 6<br>
A - 6<br>

# Exercise 15
I want you to create a function which remove duplication from an array and make it unique.<br />
For example: const arr = [1,2,2,3,3,3,4,4,5,6,6];<br>
result:[1,2,3,4,5,6];<br>
# Exercise 16
I want you to merge arrays, which is inside an object<br>
For example: const obj = { 1:[1,2,3],2:[4,5,6],3:[7,8,9]}<br>
output should be: [1,2,3,4,5,6,7,8,9].<br>
# Exercise 17
In this exercise you will create a function that takes a list of non-negative integers and strings and returns a new list with the strings filtered out.<br>
filter_list([1,2,'a','b']) ==> [1,2]<br>
filter_list([1,'a','b',0,15]) ==> [1,0,15]<br>
filter_list([1,2,'aasf','1','123',123]) ==> [1,2,123]<br>
# Exercise 18
In this exercise, you are asked to square every digit of a number and concatenate them.<br>
For example, if we run 9119 through the function, 811181 will come out, because 92 is 81 and 12 is 1.<br>
Note: The function accepts an integer and returns an integer<br>
# Exercise 19
Implement a function that adds two numbers together and returns their sum in binary. The conversion can be done before, or after the addition.<br>
The binary number returned should be a string.<br>
Examples:<br>
add_binary(1, 1) == "10" (1 + 1 = 2 in decimal or 10 in binary)<br>
add_binary(5, 9) == "1110" (5 + 9 = 14 in decimal or 1110 in binary)<br>
# Exercise 20
Check to see if a string has the same amount of 'x's and 'o's. The method must return a boolean and be case insensitive. The string can contain any char.<br>
Examples input/output:<br>
XO("ooxx") => true<br>
XO("xooxx") => false<br>
XO("ooxXm") => true<br>
XO("zpzpzpp") => true // when no 'x' and 'o' is present should return true<br>
XO("zzoo") => false<br>
# Exercise 21
Given n, take the sum of the digits of n. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.<br>
Examples<br>
    16  -->  1 + 6 = 7<br>
   942  -->  9 + 4 + 2 = 15  -->  1 + 5 = 6<br>
132189  -->  1 + 3 + 2 + 1 + 8 + 9 = 24  -->  2 + 4 = 6<br>
493193  -->  4 + 9 + 3 + 1 + 9 + 3 = 29  -->  2 + 9 = 11  -->  1 + 1 = 2<br>
# Exercise 22
Given an integral number, determine if it's a square number:<br>
In mathematics, a square number or perfect square is an integer that is the square of an integer; in other words, it is the product of some integer with itself.<br>
The tests will always use some integral number, so don't worry about that in dynamic typed languages.<br>
Examples<br>
-1  =>  false<br>
 0  =>  true<br>
 3  =>  false<br>
 4  =>  true<br>
25  =>  true<br>
26  =>  false

## Exercise 23
Write a program to reverse an array or string using loop
<br />
 input: [ 1, 2, 3 ] <br />
 output: [ 3, 2, 1 ]<br />

## Exercise 24
Write a program to combine two arrays <br />

 firstInput =  [ 1, 2, 3 ]  <br />
 secondInput = [ 4, 5, 6 ]  <br />

Output: = [ 1, 2, 3, 4, 5, 6]  <br />

## Exercise 25 
Given an array, rotate the array to the right by k steps, where k is non-negative. <br />

Input:  [1,2,3,4,5,6,7], k = 3 <br />
Output: [5,6,7,1,2,3,4] <br />
# Explanation:
rotate 1 steps to the right: [7,1,2,3,4,5,6] <br />
rotate 2 steps to the right: [6,7,1,2,3,4,5]<br />
rotate 3 steps to the right: [5,6,7,1,2,3,4]<br />

## Exercise 26 
Create a nested Create a nested for loops produce the loops produce the <br />
following output.

....1 <br />
...22<br />
..333<br />
.4444<br />
55555<br />

## Exercise 27

Given an array of integers, find the pair of adjacent elements that has the largest product and return that product.

Example

For inputArray = [3, 6, -2, -5, 7, 3], the output should be
adjacentElementsProduct(inputArray) = 21.

7 and 3 produce the largest product.

## Exercise 28 
Below we will define an n-interesting polygon. Your task is to find the area of a polygon for a given n.


Example
n= 1, output = 1;
For n = 2, the output should be
output= 5;
For n = 3, the output should be
output= 13.
For n = 4, the output should be
output = 25.


## Exercise 29 

Given the string, check if it is a palindrome.

Example

For inputString = "aabaa", the output should be
 = true;
For inputString = "abac", the output should be
 = false;
For inputString = "a", the output should be
 = true.

## Exercise 30 

Given a year, return the century it is in. The first century spans from the year 1 up to and including the year 100, the second - from the year 101 up to and including the year 200, etc.

Example

For year = 1905, the output should be
 = 20;
For year = 1700, the output should be
 = 17.

## Exercise 31 
Count frequencies of each entry in an array
For example 
const fruitBasket = ['banana', 'cherry', 'orange', 'apple', 'cherry', 'orange', 'apple', 'banana', 'cherry', 'orange', 'fig' ];

It should return an object like this 
{ banana: 2, cherry: 3, orange: 3, apple: 2, fig: 1 }

## Exercise 32 
Given a square matrix, calculate the absolute difference between the sums of its diagonals.

For example, the square matrix  is shown below: <br />

1 2 3  <br />
4 5 6  <br />
9 8 9  <br />
The left-to-right diagonal = . The right to left diagonal = . Their absolute difference is . <br />

Function description<br />

Complete the  function in the editor below. <br />

diagonalDifference takes the following parameter: <br />

int arr[n][m]: an array of integers <br />

Return <br />
int: the absolute diagonal difference <br />

Sample Input <br />

3              <br />
11 2 4         <br />
4 5 6          <br />
10 8 -12      <br />
Sample Output  <br />

15  <br />

## Exercise 33

Given an array of integers, calculate the ratios of its elements that are positive, negative, and zero. Print the decimal value of each fraction on a new line with  places after the decimal.


## Sample Input <br />
-4 3 -9 0 4 1        <br /> 
## Sample Output <br />

0.500000 <br />
0.333333 <br />
0.166667 <br />
# Explanation <br />

There are 3  positive numbers, 2 negative numbers, and 1 zero in the array. <br />
The proportions of occurrence are positive: 3/6 = 0.500000, negative: 2/6= 0.333333, 1/6= 0.166667 and zeros <br />




Output Format <br />

Print the following  lines, each to decimals: <br />

proportion of positive values <br />
proportion of negative values <br />
proportion of zeros <br />

## Exercise 34

Given an array of integers, calculate the ratios of its elements that are positive, negative, and zero. Print the decimal value of each fraction on a new line with  places after the decimal.


## Sample Input <br />
-4 3 -9 0 4 1        <br /> 
## Sample Output <br />

0.500000 <br />
0.333333 <br />
0.166667 <br />
# Explanation <br />

There are 3  positive numbers, 2 negative numbers, and 1 zero in the array. <br />
The proportions of occurrence are positive: 3/6 = 0.500000, negative: 2/6= 0.333333, 1/6= 0.166667 and zeros <br />




Output Format <br />

Print the following  lines, each to decimals: <br />

proportion of positive values <br />
proportion of negative values <br />
proportion of zeros <br />

## Exercise 35 

Given the list of items and their actual prices and sold prices. Find the number of items in sold products which has wrong prices

Example Input

Products = ['eggs', 'milk', 'cheese'];  <br />
productPrices = [2.89, 3.29, 5.79];  <br />
productSold = ['eggs', 'eggs', 'cheese', 'milk']  <br />
soldPrice = [2.89, 2.99, 5.97, 3.29];  <br />


Example Output
Here   <br />
eggs has 2.99 price which is worng 
milk has 5.97 price which is worng 
So we will return 2 in this example. 

## Exercise 36 
https://www.hackerrank.com/challenges/magic-square-forming/problem

## Exercise 37 
 make a function "delayedUpperCase(input, n)" that takes in a 2 parameters </br>
 and returns a new promise. using setTimeout, </br>
 after n milliseconds, the promise will either </br>
 resolove or reject. if the input is a string, </br>
 the promise resolves with that same string </br>
 uppercased. if the input is anything but a string </br>
 it rejects with that same input </br>

// call the function delayedUpperCase

## Exercise 38
 Download .. </br>
 Process .. </br>
 Execute .. </br>
 Solve using callbacks, promises, async/await 

 ## Exercise 39 
 Create three independent promises which will return some string like "promise 1", "promise 2", "promise 3" and store the result in one Array. 
# React.js is waiting for you
