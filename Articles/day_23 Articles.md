## Day-23 Articles

On day-23 I am practicing some problems in while loop.I have learned the basic of javascript ,How object and array works in a program .I have learned that array can store values of any datatype(primitive) , so arrays consist of strings, numbers, booleans, objects, or even other arrays.

afterwards i learnt about  while loop syntax- A  while loop is a used to executes a block of code at least once or then repeately it executes the block.

afterwards i learnt about for loop syntax- A loop is used for executing a block of statements repeatedly until a particular condition is satisfied.

main difference for while loop and for loop- In while loop we should defined the variable separately in while loop syntax.
for example let=a, let i=0, while(i>a), i=1+1.

In for loop we should defined the variable in one function itself. for example- for(let a=1, i<a, i++).And also i have learned that in javascript delete is something that delete one particular object.

first sum-

let arr=[0,1,2,3,4,5];
let i=0;
while(i<arr.length)
{
console.log("value is :"+ arr[i])
i=i+1;
}

output is-
value is:0
value is:1
value is:2
value is:3
value is:4
value is:5

second sum is-

let arr=[0,1,2,3,4,5];
let i=0;
let j=0;
while(i<arr.length,j<arr.length)
{
console.log (arr[i])
console.log (arr[i])
i++
j++
}

output is-
0
0
1
1
2
2
3
3
4
4
5
5

third sum is-

let ar=[0,1,2,3,4,5];
j=arr.length-1;
while(j>=0)
{
console.log(arr[j])
j=j-1;
}

output is-

5
4
3
2
1
0

fourth sum is-

let arr=[0,1,2,3,4,5];
let ar1=[];
let i=0;
let j=arr.length-1;
while(j>=0){
ar1[i]=arr[j]
i++
j=j-1;
console.log(ar1)

output is-

[5]
[5, 4]
[5, 4, 3]
[5, 4, 3, 2]
[5, 4, 3, 2, 1]
[5, 4, 3, 2, 1, 0]

afterwards i learnt about the function, The function is a declaration every things comes under brackets example- revarr()

function reverse(arr)
{
let revarr=[];
let i=arr.length-1;
let j=0;
while(i>=-0)
{
revarr[j]=arr[i];
i--
j++
console.log(revarr);
}
}
reverse([0,1,2,3,4,5]);

output is-

[5]
[5, 4]
[5, 4, 3]
[5, 4, 3, 2]
[5, 4, 3, 2, 1]
[5, 4, 3, 2, 1, 0]


