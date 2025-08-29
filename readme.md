
1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
<!-- ans -->
1.getElementById("id")

 -The getElementById() method returns an element with a specified value.

 -The getElementById() method returns null if the element does not exist.

2.getElementsByClassName("className")

 -Selects all elements with the given class.

 -The getElementsByClassName() method returns a collection of elements with a specified class name(s).

3.querySelector 

  -The querySelector() method returns the first element that matches a CSS selector.

  -To return all matches (not only the first), use the querySelectorAll() instead.

4.querySelectorAll

  -The querySelectorAll() method returns all elements that matches a CSS selector(s).

  -The querySelectorAll() method returns a NodeList.



2. How do you **create and insert a new element into the DOM**?
<!-- ans -->
Creating and inserting a new element into the Document Object Model (DOM) in JavaScript
Use the document.createElement()and then insert it using methods like appendChild, append, prepend, before, after, etc.



3. What is **Event Bubbling** and how does it work?
<!-- ans -->

Event bubbling in JavaScript is a mechanism where an event triggered on a child element propagates upward through its ancestors in the DOM. It allows parent elements to respond to events triggered by their child elements.

Propagation Direction: In event bubbling, the event starts at the target element and propagates upward through its parent elements to the root of the DOM.

Default Behavior: Event bubbling is enabled by default in JavaScript.

Event Listeners: If multiple event listeners are attached in the bubbling phase, they are executed in sequence, starting from the innermost target element.


4. What is **Event Delegation** in JavaScript? Why is it useful?
<!-- ans -->

Definition: Event delegation means attaching a single event listener to a parent element to handle events for all its child elements using event bubbling.

Why useful-

  -Improves performance (fewer event listeners).

  -Handles dynamically added elements.


5. What is the difference between **preventDefault() and stopPropagation()** methods?
<!-- ans -->

1. preventDefault() : Stop the browser from doing its normal thing.

  -Clicking a link normally goes to another page.
  -With preventDefault() stays on the page.

2. stopPropagation() : Stop the event from spreading to other elements.

  You click a button inside a box.Normally, the box also sees the click.With stopPropagation() → only the button reacts, box ignores it.
  

