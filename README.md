# Js-Training
Basic to advance JS training for beginners.<br />
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
Promises
# React.js is waiting for you
