# Work with Dynamic Data in D3
[link](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/work-with-dynamic-data-in-d3) [solution](./solution.html)
<br>
The last two challenges cover the basics of displaying data dynamically with D3 using the data() and enter() methods. These methods take a data set and, together with the append() method, create a new DOM element for each entry in the data set.

In the previous challenge, you created a new h2 element for each item in the dataset array, but they all contained the same text, New Title. This is because you have not made use of the data that is bound to each of the h2 elements.

The D3 text() method can take a string or a callback function as an argument:
```
selection.text((d) => d)
```
In the example above, the parameter d refers to a single entry in the dataset that a selection is bound to.

Using the current example as context, the first h2 element is bound to 12, the second h2 element is bound to 31, the third h2 element is bound to 22, and so on.
Change the text() method so that each h2 element displays the corresponding value from the dataset array with a single space and the string USD. For example, the first heading should be 12 USD.

## Tests
The first h2 should have the text 12 USD.
Waiting: The second h2 should have the text 31 USD.
Waiting: The third h2 should have the text 22 USD.
Waiting: The fourth h2 should have the text 17 USD.
Waiting: The fifth h2 should have the text 25 USD.
Waiting: The sixth h2 should have the text 18 USD.
Waiting: The seventh h2 should have the text 29 USD.
Waiting: The eighth h2 should have the text 14 USD.
Waiting: The ninth h2 should have the text 9 USD.