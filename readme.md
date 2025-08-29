
### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

Ans:getElementById :Selects one element by its id.
Example:
<div id="header">Hello</div>
const element = document.getElementById("myId");

getElementsByClassName:Selects all elements with a specific class.
const elements = document.getElementsByClassName("myClass");
<div class="box">Box 1</div>
<div class="box">Box 2</div>
const boxes = document.getElementsByClassName("box");

querySelector:Returns the first matching element.
querySelectorAll:Returns all matching elements as a NodeList


2. How do you **create and insert a new element into the DOM**?



3. What is **Event Bubbling** and how does it work?
4. What is **Event Delegation** in JavaScript? Why is it useful?
5. What is the difference between **preventDefault() and stopPropagation()** methods?
