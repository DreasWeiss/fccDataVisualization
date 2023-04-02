# Get JSON with the JavaScript fetch method
[link](https://www.freecodecamp.org/learn/data-visualization/json-apis-and-ajax/get-json-with-the-javascript-fetch-method)[solution](./solution.html)
<br>

Another way to request external data is to use the JavaScript fetch() method. It is equivalent to XMLHttpRequest, but the syntax is considered easier to understand.

Here is the code for making a GET request to /json/cats.json

```
fetch('/json/cats.json')
  .then(response => response.json())
  .then(data => {
    document.getElementById('message').innerHTML = JSON.stringify(data);
  })
```
Take a look at each piece of this code.

The first line is the one that makes the request. So, fetch(URL) makes a GET request to the URL specified. The method returns a Promise.

After a Promise is returned, if the request was successful, the then method is executed, which takes the response and converts it to JSON format.

The then method also returns a Promise, which is handled by the next then method. The argument in the second then is the JSON object you are looking for!

Now, it selects the element that will receive the data by using document.getElementById(). Then it modifies the HTML code of the element by inserting a string created from the JSON object returned from the request.
<hr/>
Update the code to create and send a GET request to the freeCodeCamp Cat Photo API. But this time, using the fetch method instead of XMLHttpRequest.

## Tests
Waiting: Your code should use the fetched data to replace the inner HTML
Waiting: Your code should make a GET request with fetch.
Waiting: Your code should use then to convert the response to JSON.
Waiting: Your code should use then to handle the data converted to JSON by the other then.
Waiting: Your code should get the element with id message and change its inner HTML to the string of JSON data.