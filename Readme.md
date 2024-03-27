# JavaScript Quote Generator

This project serves as a demonstration of DOM (Document Object Model) manipulation using JavaScript. The main goal is to create a simple web page that displays a random quote each time the user clicks a button.


## Motive of the Project

The primary purpose of the JavaScript Quote Generator is to showcase how to dynamically update elements on a webpage without reloading the entire page. Through DOM manipulation, we can change the content of specific HTML elements based on user interactions, in this case, clicking a button.

## Use of DOM

DOM manipulation is essential for dynamic web development. In this project, the DOM is used to accomplish the following tasks:

1. **Selecting Elements**: JavaScript's `document.querySelector` method is utilized to select HTML elements based on their class or ID. For instance, we select the button element with the ID `#new-quote` and the elements displaying the quote and author.

2. **Event Handling**: An event listener is attached to the "New Quote" button using `addEventListener`. When the button is clicked, a function is executed.

3. **Updating Content**: Inside the event handler function, a random quote is selected from an array of quotes. The `innerText` property of the quote and author elements is then updated with the selected quote and its respective author, respectively. This updating of content demonstrates how the DOM can be modified dynamically based on user actions.

## How It Works

1. Upon loading the page, an initial quote and author are displayed.
2. When the "New Quote" button is clicked, an event is triggered.
3. The event handler function generates a random index to select a quote from an array of predefined quotes.
4. The selected quote and its author are then displayed on the webpage by updating the corresponding elements' inner text.


