# Add Classes with D3
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/add-classes-with-d3) [solution](./solution.html)
<br>
Using a lot of inline styles on HTML elements gets hard to manage, even for smaller apps. It's easier to add a class to elements and style that class one time using CSS rules. D3 has the attr() method to add any HTML attribute to an element, including a class name.

The attr() method works the same way that style() does. It takes comma-separated values, and can use a callback function. Here's an example to add a class of container to a selection:
```
selection.attr("class", "container");
```
Note that the class parameter will remain the same whenever you need to add a class and only the container parameter will change.
Add the attr() method to the code in the editor and put a class of bar on the div elements.



## Tests
Waiting: Your div elements should have a class of bar.
Waiting: Your code should use the attr() method.