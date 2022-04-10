# Lecture 13 CSS Hover Effect and Display Property 

## Hover Property of CSS

The Hover Property gets activated when mouse goes on element. 
Remember, to apply any property on any element in css, we need to apply selector, be it tag name, class name or id.

### 💻Example:

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
### 

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

**Block**

* These elements starts with new line. 
* They tries to take all the available space.
* We can specify Height and Width to them.   
For e.g. all heading tags, division tag, paragraph tag, etc. 

**Inline-Block**

* Elements in Same line ( if space is available )
* Height and Widht can be specified. 

### 🏠 Homework 

>1️⃣ Create cards using display properties similar to courses on RTC website. 
