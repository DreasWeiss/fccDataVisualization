# Change Text with click Events
[link](https://www.freecodecamp.org/learn/data-visualization/json-apis-and-ajax/change-text-with-click-events) [solution](./solution.html)
<br>

When the click event happens, you can use JavaScript to update an HTML element.

For example, when a user clicks the Get Message button, it changes the text of the element with the class message to say Here is the message.

This works by adding the following code within the click event:
```
document.getElementsByClassName('message')[0].textContent="Here is the message";
```
Add code inside the onclick event handler to change the text inside the message element to say Here is the message.

## Tests
Waiting: Your code should use the document.getElementsByClassName method to select the element with class message and set its textContent to the given string.