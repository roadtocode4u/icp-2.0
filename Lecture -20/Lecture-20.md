# Lecture 20 Flexboxes

## Flexbox: 

* The term flexbox is made up by joining two terms, 1) Flex extending to flexible, meaning anything which can be bended to a great
extent without breaking is termed as flexible, and 2) box. 

* So the boxes which are very flexible for design specifications and could be configured easily are termed as Flexboxes. 

### Flexbox consist of two components:

1) Container: Containers are widely used in front-end.
2) Items: A container consist of items, together they make a flexbox. 

### Flow-direction:

Items can be displayed in four directions:

* row : left to right 
💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  flex-direction: row;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 
![Screenshot (78)](https://user-images.githubusercontent.com/43013697/164728185-8eea4a4b-100a-4352-bef5-699ba2d99748.png)


* row-reverse: right to left
💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  flex-direction: row-reverse;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 
![Screenshot (79)](https://user-images.githubusercontent.com/43013697/164728395-877b360f-e185-4b3a-9f52-4094d1c68110.png)

* column: same as row but top to bottom
💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  flex-direction: column;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 
![Screenshot (80)](https://user-images.githubusercontent.com/43013697/164728904-8a622a95-5848-4112-ad34-2b62e6482619.png)


* column-reverse: same as row-reverse but bottom to top

💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  flex-direction: column;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 

![Screenshot (81)](https://user-images.githubusercontent.com/43013697/164729983-be7eee86-8150-4dfc-8422-2c6c144a2c7f.png)

### Justify-Content:

It has six properties:

* Flex-start

💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  justify-content: flex-start;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 
![Screenshot (78)](https://user-images.githubusercontent.com/43013697/164731694-00a3592f-c639-43a2-ae45-a5e8dc92c782.png)


* Flex-end
💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  justify-content: flex-end;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 
![Screenshot (79)](https://user-images.githubusercontent.com/43013697/164731883-e78dab45-ee39-434b-be93-997edd9ebe94.png)

* Center

💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  justify-content: center;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 
![Screenshot (83)](https://user-images.githubusercontent.com/43013697/164732135-a8e9e17a-21a3-45f5-90f3-01f6168900eb.png)

* Space-between

💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  justify-content: space-between;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 

![Screenshot (84)](https://user-images.githubusercontent.com/43013697/164732427-d000bdd1-f4db-4cdb-88ac-b6c506872d81.png)


* Space-around

💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  justify-content: space-around;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 

![Screenshot (85)](https://user-images.githubusercontent.com/43013697/164732525-43216070-fba1-402b-92d3-565a7343f036.png)


* Space-evenly

💻 Example:
```html
<!DOCTYPE html>
<html>
<head>
<title>Flex Box</title>
<style>
.item {
  display: flex;
  background-color: tomato;
  width: 100px;
  height: 100px;
  margin: 10px;
  font-size: 50px;
  color: white;
  
}

.container {
  display: flex;
  background-color: #9212e8;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
  justify-content: space-evenly;
}
</style>
</head>
<body>

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
</div>



</body>
</html>
``` 
![Screenshot (86)](https://user-images.githubusercontent.com/43013697/164732841-622a70da-fabc-41a8-b9b8-c70fe2bf8a7f.png)


## 🏡 Homework:

Use all six Justify-content property to display different, fruits, vegitables, animals, vehicles, etc. 
