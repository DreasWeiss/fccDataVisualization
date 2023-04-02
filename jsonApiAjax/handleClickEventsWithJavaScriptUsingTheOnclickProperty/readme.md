# Handle Click Events with JavaScript using the onclick property
[link](https://www.freecodecamp.org/learn/data-visualization/json-apis-and-ajax/handle-click-events-with-javascript-using-the-onclick-property) [solution](./solution.html)
<br>

You want your code to execute only once your page has finished loading. For that purpose, you can attach a JavaScript event to the document called DOMContentLoaded. Here's the code that does this:
```
document.addEventListener('DOMContentLoaded', function() {

});
```
You can implement event handlers that go inside of the DOMContentLoaded function. You can implement an onclick event handler which triggers when the user clicks on the #getMessage element, by adding the following code:
```
document.getElementById('getMessage').onclick = function(){};
```
Add a click event handler inside of the DOMContentLoaded function for the element with id of getMessage.


## Tests
Waiting: Your code should use the document.getElementById method to select the element whose id is getMessage.
Waiting: Your code should add an onclick event handler.