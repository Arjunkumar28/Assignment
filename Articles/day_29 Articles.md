## Day-29 Articles

On day29 I learnt about how to built a programming code for tower of hanoi. while solving this tower of hanoi i am facing many difficulties to solve, but it is the nice experience for me and i will not forget this problem till my life ends.

**Tower of hanoi problem:**

- let a=[1,2,3,4]
- let b=[]
- let c=[]
- let len=a.length;
- let num=Math.pow(2,a.length);

- if(len%2===0)
- :{
- for (i=0;i<num-1;i++)
- {
- if(i%3===0)
- {
- if(b.length===0)
- {
- b.unshift(a[0])
- a.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a[0]<b[0])
- {
- b.unshift(a[0])
- a.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a.length===0)
- {
- a.unshift(b[0])
- b.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a[0]>b[0])
- {
- a.unshift(b[0])
- b.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- }


- if(i%3===1)
- {
- if(c.length===0)
- {
- c.unshift(a[0])
- a.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a[0]<c[0])
- {
- c.unshift(a[0])
- a.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a.length===0)
- {
- a.unshift(c[0])
- c.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a[0]>c[0])
- {
- a.unshift(c[0])
- c.shift();
- console.log(a)
- console.log(b);
- console.log(c);
- }       
- }


- if(i%3===2)
- {
     
- if(c.length===0)
- {
- c.unshift(b[0])
- b.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(b[0]<c[0])
- {
- c.unshift(b[0])
- b.shift();
- console.log(a);
- console.log(b);
- console.log(c);  
- }
- else if(b.length===0)
- {
- b.unshift(c[0])
- c.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(b[0]>c[0])
- {
- b.unshift(c[0])
- c.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- }
- }
- }

- else
- {

- for (let j=0;j<num-1;j++)
- {
- if(j%3===0)
- {
- if(c.length===0)
- {
- c.unshift(a[0])
- a.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a[0]<c[0])
- {
- c.unshift(a[0])
- a.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a.length===0)
- {
- a.unshift(c[0])
- c.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a[0]>c[0])
- {
- a.unshift(c[0])
- c.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }        
- }


- if(j%3===1)
- {
- if(b.length===0)
- {
- b.unshift(a[0])
- a.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a[0]<b[0])
- {
- b.unshift(a[0])
- a.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a.length===0)
- {
- a.unshift(b[0])
- b.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(a[0]>b[0])
- {
- a.unshift(b[0])
- b.shift();
- console.log(a)
- console.log(b);
- console.log(c);
- }
- }


- if(j%3===2)
- {
     
- if(c.length===0)
- {
- c.unshift(b[0])
- b.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(b[0]<c[0])
- {
- c.unshift(b[0])
- b.shift();
- console.log(a);
- console.log(b);
- console.log(c);  
- }
- else if(b.length===0)
- {
- b.unshift(c[0])
- c.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- else if(b[0]>c[0])
- {
- b.unshift(c[0])
- c.shift();
- console.log(a);
- console.log(b);
- console.log(c);
- }
- }
- }
- }


Algorithm for Tower of hanoi

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


