# Lecture 13 CSS Hover Effect and Display Property 

## Hover Property of CSS

The Hover Property gets activated when mouse goes on element. 
Remember, to apply any property on any element in css, we need to apply selector, be it tag name, class name or id.

**💻Example:**

```
<html>
    <head>
        <title>
            Hover Effect
        </title>
        <style>
            button
            {
                background-color: tomato;
            }
            button:hover
            {
                background-color: yellow;
            }
        </style>
    </head>
    <body>

        <button>Click Me!😉</button> 
    </body>
</html>
```
### Output: 
**Normal Output**


![Screenshot (220)](https://user-images.githubusercontent.com/90567283/162619253-9d408cdf-30f6-41c9-9109-f32249be2816.png)


**Output with Hover Effect**


![Screenshot (221)](https://user-images.githubusercontent.com/90567283/162619341-24464ff2-7760-4172-a12f-516d30b6885b.png)

## Display Property in CSS

In general we have 3 types of display properties:
1. Inline
2. Block
3. Inline-Block

**Inline:** 

* Element will start from same line, or we can say that element will not start from new line. 
* It will utilize the reamining space. 
* It cannot be specified Height or Width. 
For e.g. Images, anchor tag, italic tag, span tag, etc.

**💻Example:**

![Screenshot (223)](https://user-images.githubusercontent.com/90567283/163569914-93278b2f-3ab4-4ff7-9470-30e302adb9b0.png)

**Block**

* These elements starts with new line. 
* They tries to take all the available space.
* We can specify Height and Width to them.   
For e.g. all heading tags, division tag, paragraph tag, etc. 

**💻Example:**

![Screenshot (225)](https://user-images.githubusercontent.com/90567283/163664605-956d770e-8ebe-4569-acf5-ffccfaaf0056.png)

**Inline-Block**

* Elements in Same line ( if space is available )
* Height and Widht can be specified. 

**💻Example:**

![Screenshot (224)](https://user-images.githubusercontent.com/90567283/163569942-bf35e408-b161-4195-b44f-748eb1cbc7d4.png)

### 🏠 Homework 

>1️⃣ Create cards using display properties similar to courses on RTC website. 
