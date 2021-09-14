## Day-31 Articles

On day 31 I learnt about some function key like return, break,switch,case,continue, string interpolation and string concatenation.

**Return-** The return statement is used in function and it will stop executing and it will return what we calling. for example

- function add(a,b)
- {
- return a+b;
- }
- add(1,2)

output is - 3

**Break-** The break statement is used to break the current looping and it will print . for example

- let i = 0;
- while (i < 6)
- {
- if (i === 3) {
- break;
- }
- i = i + 1;
- }
- console.log(i);

output is - 3

**switch-** The switch statement is used to create a different conditional statements and used to compare the cases

- function printAValue(num){
- switch (num%3) {
- case 0:
- console.log("value is 3");
- break;
- case 1:
- console.log("value is 2");
- break;
- case 2:
- console.log("value is 4");
- break;
- }
- }


After that I am practicing some problems

problem no:1

- let a=5;
- let str = "";
- for(let i = 1; i <=a; i++ )
- {
- str=str.concat("  ")

- for(let j = 0; j <=a-i; j++)
- {
- str=str.concat("  ")
- }

- for (let k=0; k<i; k++)
- {
- str=str.concat(k+1);
- }
- str=str.concat ("\n");
- }
- console.log(str)

output is
-     1
-    12
-   123
-  1234
- 12345

problem no: 2


- let a=5;
- let str = "";
- for(let i = 1; i <=a; i++ )
- {
- str=str.concat("  ")

- for(let j = 1; j <=a-i; j++)
- {
- str=str.concat(j+1);
- }

- str=str.concat ("\n");
- }
- console.log(str)

output is

- 2345
- 234
- 23
- 2

problem no:3

- let n = 5;
- let str = "";
- for (let i = n; i >= 1; i--) 
- {
- for (let j = 0; j <i; j++) 
- {
- str =str.concat(" ");
- }
- for(j=i;j<=n;j++)
- {
- str=str.concat (j);
- }
- str=str.concat ("\n");
- }
- console.log(str);

output is

-     5
-    45
-   345
-  2345
- 12345

