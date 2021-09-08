## Day-27 Articles

On day27 I am practicing some problems

first sum-

* let a=[4,3,2,1];
* let b=[];
* let c=[];

* a.pop();
* b.unshift(1);
* console.log(a);
* console.log(b);
* console.log(c);

* a.pop();
* c.unshift(2);
* console.log(a);
* console.log(b);
* console.log(c);

* b.shift();
* c.push(1);
* console.log(a);
* console.log(b);
* console.log(c);

* a.pop();
* b.unshift(3);
* console.log(a);
* console.log(b);
* console.log(c);

* c.pop();
* a.push(1);
* console.log(a);
* console.log(b);
* console.log(c);

* c.shift();
* b.push(2);
* console.log(a);
* console.log(b);
* console.log(c);

* a.pop();
* b.push(1);
* console.log(a);
* console.log(b);
* console.log(c);

* a.shift();
* c.unshift(4);
* console.log(a);
* console.log(b);
* console.log(c);

* b.pop();
* c.push(1);
* console.log(a);
* console.log(b);
* console.log(c);

* b.pop();
* a.push(2);
* console.log(a);
* console.log(b);
* console.log(c);

* c.pop();
* a.push(1);
* console.log(a);
* console.log(b);
* console.log(c);

* b.pop();
* c.push(3);
* console.log(a);
* console.log(b);
* console.log(c);

* a.pop();
* b.push(1);
* console.log(a);
* console.log(b);
* console.log(c);

* a.pop();
* c.push(2);
* console.log(a);
* console.log(b);
* console.log(c);

* b.pop();
* c.push(1);
* console.log(a);
* console.log(b);
* console.log(c);


Second sum:

* function toh (n,a,b,c)
* {
* if(n>0)
* {
* toh(n -1,a,c,b);
* console.log('move a disk '+n+' from '+a+' to '+c);
* toh(n -1,b,a,c);
* }
* };
* var n=4;
* toh(n,'a','b','c');

output-

* move a disk 1 from a to b
* move a disk 2 from a to c
* move a disk 1 from b to c
* move a disk 3 from a to b
* move a disk 1 from c to a
* move a disk 2 from c to b
* move a disk 1 from a to b
* move a disk 4 from a to c
* move a disk 1 from b to c
* move a disk 2 from b to a
* move a disk 1 from c to a
* move a disk 3 from b to c
* move a disk 1 from a to b
* move a disk 2 from a to c
* move a disk 1 from b to c


