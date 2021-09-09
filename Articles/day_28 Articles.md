## Day-28 Articles

On day 28 I learnt the algorithm of tower of hanoi and I am trying to solve the solve the problem

steps for the tower of hanoi,

* step1- start

* step2- get the no of disk

* step3- find no of steps with (2^nod)-1

* step4- 1. move disk from A and B
	 2. move disk from A and C
	 3. move disk from B and C

* step5- check if no of moves is less than steps

* step6- else if check the nod id odd.

* step7- 1. move disk from A and C
         2. move disk from A and B
         3. move disk from B and C

* step8- check if no of moves is less than steps

* step9- stop

program code-

* function toh(a)
* {

* let b=[];
* let c=[];
* for(i=1;i<a.length;i++)
* {

* if(i%3===0)
* {
* let x=a.shift()
* let y=b.shift()
* if(a[0] < b[0])
* {
* b.unshift(x);
* b.unshift(y);
* }
* console.log(a);
* console.log(b);
* console.log(c);


* if(a[0] > b[0])
* {
* b.unshift(y);
* b.unshift(x);
* }
* console.log(a);
* console.log(b);
* console.log(c);
* }


* if(i%3===1)
* {
* let x=a.shift()
* let y=c.shift()
* if(a[0] < c[0])
* {
* c.unshift(x);
* c.unshift(y);
* }
* console.log(a);
* console.log(b);
* console.log(c);


* if(a[0] > c[0])
* {
* c.unshift(y);
* c.unshift(x);
* }
* console.log(a);
* console.log(b);
* console.log(c);
* }

* if(i%3===2)
* {
* let x=b.shift()
* let y=c.shift()
* if(b[0] < c[0])
* {
* c.unshift(x);
* c.unshift(y);
* }
* console.log(a);
* console.log(b);
* console.log(c);


* if(b[0] > c[0])
* {
* c.unshift(y);
* c.unshift(x);
* }
* console.log(a);
* console.log(b);
* console.log(c);
* }

* }


* for(j=1;j<a.length;j++)
* {

* if(j%3===0)
* {
* let x=a.shift()
* let y=c.shift()
* if(a[0] < c[0])
* {
* c.unshift(x);
* c.unshift(y);
* }
* console.log(a);
* console.log(b);
* console.log(c);


* if(a[0] > c[0])
* {
* c.unshift(y);
* c.unshift(x);
* }
* console.log(a);
* console.log(b);
* console.log(c);
* }


* if(i%3===1)
* {
* let x=a.shift()
* let y=b.shift()
* if(a[0] < b[0])
* {
* b.unshift(x);
* b.unshift(y);
* }
* console.log(a);
* console.log(b);
* console.log(c);

* if(a[0] > b[0])
* {
* b.unshift(y);
* b.unshift(x);
* }
* console.log(a);
* console.log(b);
* console.log(c);
* }



* if(j%3===2)
* {
* let x=c.shift()
* let y=b.shift()
* if(c[0] < b[0])
* {
* b.unshift(x);
* b.unshift(y);
* }
* console.log(a);
* console.log(b);
* console.log(c);


* if(c[0] > b[0])
* {
* b.unshift(y);
* b.unshift(x);
* }
* console.log(a);
* console.log(b);
* console.log(c);
* }

* }

* }toh([1,2,3])






