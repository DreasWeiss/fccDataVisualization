# Select a Group of Elements with D3
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/select-a-group-of-elements-with-d3) [solution](./solution.html)
<br>
D3 also has the selectAll() method to select a group of elements. It returns an array of HTML nodes for all the items in the document that match the input string. Here's an example to select all the anchor tags in a document:
```
const anchors = d3.selectAll("a");
```
Like the select() method, selectAll() supports method chaining, and you can use it with other methods.
Select all of the li tags in the document, and change their text to the string list item by chaining the .text() method.

## Tests
Waiting: There should be 3 li elements on the page, and the text in each one should say list item. Capitalization and spacing should match exactly.
Waiting: Your code should access the d3 object.
Waiting: Your code should use the selectAll method.