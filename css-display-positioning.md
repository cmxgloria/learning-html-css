```
//css-display-positioning
//html
<!DOCTYPE html>
<html>
<head>
  <title>Please Participate in Our Survey!</title>
  <link href="https://fonts.googleapis.com/css?family=Oswald:300,700|Varela+Round" rel="stylesheet">
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>

  <header>
    <ul>
      <li>Question 1</li>
      <li>Question 2</li>
      <li>Question 3</li>
      <li>Question 4</li>
      <li>Question 5</li>
      <li>Question 6</li>
    </ul>
  </header>
  
  <div class="welcome">
    <h1><strong>Welcome</strong> to our survey!</h1>
    <p>We're looking forward to getting your answers so we can make sure our products and services are the best they can be!</p>
  </div>

  <div class="question">
    <h4>Question 1</h4>
    <h2>I like participating in physical activity such as running, swimming, or biking.</h2>

    <div class="answer">
      <h3>Disagree</h3>
    </div>

    <div class="answer">
      <h3>Neutral</h3>
    </div>

    <div class="answer">
      <h3>Agree</h3>
    </div>
  </div>

  <div class="question">
    <h4>Question 2</h4>
    <h2>I try to keep up to date with the latest fashion in active wear.</h2>

    <div class="answer">
      <h3>Disagree</h3>
    </div>

    <div class="answer">
      <h3>Neutral</h3>
    </div>

    <div class="answer">
      <h3>Agree</h3>
    </div>
  </div>

  <div class="question">
    <h4>Question 3</h4>
    <h2>I purchase clothing online regularly.</h2>

    <div class="answer">
      <h3>Disagree</h3>
    </div>

    <div class="answer">
      <h3>Neutral</h3>
    </div>

    <div class="answer">
      <h3>Agree</h3>
    </div>
  </div>

  <div class="question">
    <h4>Question 4</h4>
    <h2>I try to buy goods that are designed and/or manufactured in my home country.</h2>

    <div class="answer">
      <h3>Disagree</h3>
    </div>

    <div class="answer">
      <h3>Neutral</h3>
    </div>

    <div class="answer">
      <h3>Agree</h3>
    </div>
  </div>

  <div class="question">
    <h4>Question 5</h4>
    <h2>I look to famous athletes when trying to choose what to wear when training.</h2>

    <div class="answer">
      <h3>Disagree</h3>
    </div>

    <div class="answer">
      <h3>Neutral</h3>
    </div>

    <div class="answer">
      <h3>Agree</h3>
    </div>
  </div>
<footer>
  <h3>Thanks for taking our survey!</h3>
  </footer>
</body>
</html>

//css
body {
  background-color: #FFF;
  margin: 0 auto;
}

header {
  background-color: #466995;
  border-bottom: 1px solid #466995;
  position: fixed;
  width: 100%;
  z-index: 10;
}

ul {
  margin: 30px auto;
  padding: 0 20px;
  text-align: center;
}

li {
  color: #FFF;
  font-family: 'Oswald', sans-serif;
  font-size: 16px;
  font-weight: 300;
  text-transform: uppercase;
  display: inline-block;
  width: 80px;

}

li:hover {
  color: #DBE9EE;
}

h1 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 32px;
  font-weight: 300;
  text-transform: uppercase;
}

h2 {
  color: #333;
  font-family: 'Varela Round', sans-serif;
  font-size: 26px;
  font-weight: 100;
  margin: 0 auto 20px auto;
}

h3 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 18px;
  text-align: center;
  font-weight: 700;
  text-transform: uppercase;
  padding: 30px;
}

h4 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 18px;
  font-weight: 300;
  letter-spacing: 2px;
  text-align: center;
  text-transform: uppercase
}

p {
  color: #333;
  font-family: 'Varela Round', sans-serif;
  font-size: 18px;
}

footer {
  background-color: #DBE9EE;
  text-align: center;
}

.welcome {
  background-color: #DBE9EE;
  box-sizing: border-box;
  padding: 40px;
  text-align: center;
  width: 100%;
  position: relative;
  top: 50px;
  
}

.question {
  text-align: center;
  position: relative;
  top: 40px;
}

.answer {
  border: 1px solid #466995;
  margin: 20px;
  display: inline-block;
}

.answer:hover {
  background: #C0D6DF;
  color: #FFF;
}
footer{
  height: 100px;
}

```

// position: static, fixed(it won't move regardless user scroll down), absolute and relative

```
The z-index property controls how far “back” or how far “forward” an element should appear on the web page when elements overlap. This can be thought of the depth of elements, with deeper elements appearing behind shallower elements.
```

```
display property: inline, block, and inline-block.
The default display for some tags, such as <em>, <strong>, and <a>, is called inline. Inline elements have a box that wraps tightly around their content, only taking up the amount of space necessary to display their content and not requiring a new line after each element. 

Some elements are not displayed in the same line as the content around them. These are called block-level elements. These elements fill the entire width of the page by default, but their width property can also be set. 

The third value for the display property is inline-block. Inline-block display combines features of both inline and block elements. Inline-block elements can appear next to each other and we can specify their dimensions using the width and height properties.
```
//
