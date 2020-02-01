<h4> What is Function Expressions? </h4>
<p>Another way to define a function is with a function expression. In this we can assign function to a variable, by using that variable we can call function.</p>

```javascript
var add = function(x,y) {
		return x + y;
	}
var sum = add(5,4);
console.log("sum of 5+4", sum);
```
<h3>Please open the console and see the log </h3>
<h4 style="color:green;">Press Ctrl + Shift + J (Windows / Linux) or Cmd + Opt + J (Mac) to open console. </h4>

```html
<iframe id="preview"></iframe>
```
<p>In above example, to add variable we assigned addition function and then we called add function by passing 5 and 4.</p>
<p> Unlike declared functions, function expressions are not hoisted: they are created when the execution flow reaches them. As such, function expressions can be used only after they are defined.</p>
