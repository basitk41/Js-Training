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
