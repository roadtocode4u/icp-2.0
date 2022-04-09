# Lecture-12 CSS Properties and Cards
## Text-align property
The text-align property displays the text in value applied like left, right, center, etc. Remember, it will only work with text like, paragraphs, <a> tag, text, etc. 
### Property Values
1. left
2. right
3. center
4. justify
#### 💻 Example
```html
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  text-align: center;
}

p.date {
  text-align: right;
}

p.main {
  text-align: justify;
}
</style>
</head>
<body>

<h1>CSS text-align Example</h1>

<p class="date">April, 2022</p>

<p class="main">This is an example of css text align property</p>

<p><b>Note:</b> Resize the browser window to see how the value "justify" works.</p>

</body>
</html>

```
#
## Box-Shadow Property
The box-shadow property is used to diplay shadows around objeects like cards, divisions, etc.

### Basic Syntax:  
 
* box-shadow: horizontal verticle blur color; 

**The first value in the above example will decide how much the shadow will be horizontal, second value will diecide verticle, third value blur and thikness of shadow and color value, color of the shadow.** 
  
### 💻 Example
```html
<!DOCTYPE html>
<html>
<head>
<style> 
#example1 {
  border: 1px solid;
  padding: 10px;
  box-shadow: 5px 10px;
}

#example2 {
  border: 1px solid;
  padding: 10px;
  box-shadow: 5px 10px #888888;
}

#example3 {
  border: 1px solid;
  padding: 10px;
  box-shadow: 5px 10px red;
}
</style>
</head>
<body>

<h1>The box-shadow Property</h1>
<p>The box-shadow property defines the shadow of an element:</p>

<h2>box-shadow: 5px 10px:</h2>
<div id="example1">
  <p>A div element with a shadow.</p>
</div>

<h2>box-shadow: 5px 10px #888888:</h2>
<div id="example2">
  <p>You can also define the color of the shadow. Here the shadow color is grey.</p>
</div>

<h2>box-shadow: 5px 10px red:</h2>
<div id="example3">
  <p>A red shadow.</p>
</div>

</body>
</html>
```
# Creating a Card with CSS
### 💻 Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CARD</title>
    <style>
        .card{
            width: 150px;
            height: 180px;
            border: 1px solid black;
            margin-left: auto;
            margin-right: auto;
            border-radius: 10px;
            padding: 15px;

            box-shadow: 0px 0px 10px #595959;
        }
        
        .btn-add{
            background-color: tomato;
            border: 1px solid black;
            padding: 5px;
            border-radius: 10px;
            width: 100px;
            margin-left: auto;
            margin-right: auto;
            display: block;
            margin-top: 20px;
        }
        .product-image{
            height: 100px;
            width: 150px;
        }
       
    </style>
</head>
<body>
    <div class="card">
        <img  src="./speakers.jpeg" class="product-image">
        <button class="btn-add">Add To Card</button>
    </div>
    
</body>
</html>
```
![Output](/output.png)
#
## 🏠 Homework 

>1️⃣ Create a webpage and implement atleast 3 cards.

