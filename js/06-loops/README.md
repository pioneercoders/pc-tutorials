<p>When we want execute a block of code repeatedly. The best solution for repetitive task is loops(iterations).</p>
<p>There are different types of loops available which performs same actions. but mostly we will use three types of loops. They are</p>
<ul>
	<li>for loop</li>
	<li>while loop</li>
	<li>do while loop</li>
</ul>

<h4>For loop</h4>
<p>The flow chart of a for loop in JavaScript would be as follows -</p>

![jsforloop](https://github.com/pioneercoders/pc-tutorials/blob/master/js/images/jsforloop.jpg)


<h5>Syntax:</h5>

```javascript
for (initialization; testcondition; increment/decrementexpression){
Statements to be executed if test condition is true
}
```

<p>for loop will repeats untill the specified condition is false.</p>
<p>When a for loop executes, the following occurs:</p>
<p><b>initialization</b>: we can initialize one or more variables using comma seperator. Note that initialization done only at the begining of the loop(for first iteration).</p> 
<p><b>condition</b>: we can set a condition for 'for' loop, the loop will be repeated until this condition is true. The loop will be teminated 	if the condition is false. if the condition is not specified.then it assumed to be true and loop will be repeated infinitely. </p>	
<p><b>increment/decrement Expression</b>: here we can specify increment and decrement of the initialized variables</p>


<h3>Please open the console and see the log </h3>
<h4 style="color:green;">Press Ctrl + Shift + J (Windows / Linux) or Cmd + Opt + J (Mac) to open console. </h4>
<!--try with different assignment operators like a ^= b, a |= b, a &= b etc. -->

```javascript
	for (var i=0; i<=3; i++){
		console.log("i value in for loop " + i);
	}
 ```
 
 <div>
        <iframe id="preview"></iframe>
    </div>



<h4>While Loop</h4>
<p>The flow chart of a while loop in JavaScript would be as follows</p>

![jswhileloop](https://github.com/pioneercoders/pc-tutorials/blob/master/js/images/jswhileloop.jpg)


<h5>Syntax:</h5>

```javascript
while(condition){	
	code to be executed
}
```

<p>block of code inside while loop is executed as long as the specified condition is true. The loop is terminated if the condition becomes false</p>
	
<h3>Please open the console and see the log </h3>
<h4 style="color:green;">Press Ctrl + Shift + J (Windows / Linux) or Cmd + Opt + J (Mac) to open console. </h4>
<!--try with different assignment operators like a ^= b, a |= b, a &= b etc. -->

```javscript
var i=0;
while (i<=3){
	console.log("i value in for while loop  " + i);
	i = i + 1;
	}
```

<div>
        <iframe id="preview1"></iframe>
</div>
		
<h4>do..while Loop</h4>
<p>The flow chart of a do-while loop in JavaScript would be as follows -</p>

![jsdowhileloop](https://github.com/pioneercoders/pc-tutorials/blob/master/js/images/jsdowhileloop.jpg)

<h5>Syntax:</h5>

```javascript
do{
	code to be executed
} while (expression);
````



<p>in the do wile loop statements are executed first, then conditional check happens at the end of the loop. At the end of every execution condition is checked. If the condition is false control passes to next stament in file.</p>

<h3>Please open the console and see the log </h3>
<h4 style="color:green;">Press Ctrl + Shift + J (Windows / Linux) or Cmd + Opt + J (Mac) to open console. </h4>
<!--try with different assignment operators like a ^= b, a |= b, a &= b etc. -->

```javascript
var i=0;
do{
	console.log("i value in do while loop  " + i);
	i = i + 1;
	}
	while (i<=3);
```

<div>
        <iframe id="preview2"></iframe>
</div>
