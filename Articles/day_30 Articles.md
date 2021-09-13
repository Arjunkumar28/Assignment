## Day-30 Articles

On day 30 I am practiciing some problem in javascript

problem no: one

* let a=5;
* let str = "";
* for(let i = 0; i < a; i++ )
* {
* for(let j = 0; j < a; j++)
* {
* if( j >= i )
* {
* str=str.concat ("*");
* }
* }
* str=str.concat ("\n");
* }
* console.log(str);

output is-

- *****
- ****
- ***
- **
- *


problem no: two

* let a=5;
* let str = "";
* for(let i = 0; i < a; i++ )
* {
* for(let j = 0; j < a; j++)
* {
* if( j <= i )
* {
* str=str.concat ("*");
* }
* }
* str=str.concat ("\n");
* }
* console.log(str);

output is-

- *
- **
- ***
- ****
- *****

problem no: three

* let a=5;
* let str = "";
* for(let i = 0; i < a; i++ )
* {
* for(let j = 0; j < a-i; j++)
* {
* str=str.concat (j+1);
* }
* }
* str=str.concat ("\n");
* }
* console.log(str);


output-

- 12345
- 1234
- 123
- 12
- 1

problem no: four

* let a=5;
* let str = "";
* for(let i = 0; i < a; i++ )
* {
* for(let j = 5; j < i; j--)
* {
* str=str.concat (j);
* }
* }
* str=str.concat ("\n");
* }
* console.log(str);


output is-

- 54321
- 5432
- 543
- 54
- 5


problem no: five

* let a=5;
* let str = "";
* for(let i = 0; i < a; i++ )
* {
* for(let j = 0; j < a; j++)
* {
* if( j >= i )
* {
* str=str.concat ("*  ");
* }
* }
* str=str.concat ("\n");
* }
* console.log(str);

output is-

- *  *  *  *  *
- *  *  *  *
- *  *  *
- *  *
- *

problem no: sixth

* let a=5;
* let str = "";
* for(let i = 0; i < a; i++ )
* {
* for(let j = 0; j < a; j++)
* {
* if( j >= i )
* {
* str=str.concat ("*_");
* }
* }
* str=str.concat ("\n");
* }
* console.log(str);

output is-

- *_*_*_*_*

- *_*_*_*

- *_*_*

- *_*

- *-





