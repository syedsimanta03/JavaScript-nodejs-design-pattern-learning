***
<h2 align="center">
🎉 Nodejs Design Patterns For Beginners! 🎉
</h2>
<p align="center">
A topic that can easily make anyone's mind wobble. Here I try to make them stick in to your mind (and maybe mine) by explaining them in the <i>simplest</i> way possible. 
<br/>
   This will help you to learn Nodejs faster
</p>

​             

<h3 align="center">
     🔗 LIVE URL: <a href="https://syedsimanta03.github.io/JavaScript-Dessign-Pattern">"Design patterns by Simanta"</a> 
</h3>

<!--I build my own online/local playground when learning new topic or language. There are tons of resources out there where you can learn the same topics described here. But if you are like me, want to learn in an organized or simplest way then this is good for you.--> 

***

## :arrow_right:  Arrow function operator 

 An **arrow function** expression is a syntactically compact alternative to a regular **function** expression, although without its own bindings to the this , arguments , super , or new. ... **Arrow function** expressions are ill suited as methods, and they cannot be used as constructors. 

ex-1

```javascript
"use strict";

var numbers = [2, 6, 7, 8, 1];
var even = numbers.filter(function(x) {
  return x % 2 === 0;
});

console.log(even);
```

ex-2: direct return for one line code

```javascript
"use strict";

var numbers = [2, 6, 7, 8, 1];
var even = numbers.filter(x => x%2 === 0);

console.log(even);
```

ex-2: arrow fun with filter

```javascript
"use strict";

var numbers = [2, 6, 7, 8, 1];
var even = numbers.filter((x) => {
  if (x % 2 === 0) {
    console.log(x + ' is even!');
    return true;
  }
});

console.log(even);
```

------



##  :dancers: let and const keywords 