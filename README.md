# p5.js
An easy introduction to p5.js

So that I do not have to explain ~~wtf~~ p5.js is.


**p5.js** lets you create and interact with a canvas in a very easy way.

**p5.js** itself is just an **JavaScript** file that u can include into your html file.

If your familiar with *processing**, **p5.js** is just like **processing** but then with **JavaScript**.

( **processing** and **p5.js** are simplified versions of *Java* and *JavaScript*. )

***


To include **p5.js** you just have to download the file and include it inside your html file.

```html
<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>p5.js</title>
</head>
    <body>
        <script type="text/javascript" src="p5.js"></script>
        <script type="text/javascript" src="script.js"></script>
    </body>
</html>
```

***

Now after including **p5.js** you can make a second js file where you can begin writing code from the [**p5.js** library](https://p5js.org/reference/).

```javascript
function setup() {
    createCanvas(600, 300);
}

function draw() {
    background(200);
    ellipse(56, 46, 55, 55);
}
```

If you need help learing *p5.js*, then [The Coding Train](https://www.youtube.com/watch?v=yPWkPOfnGsw&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA) can definitly help you.
