# Adding 10 Elements to a List

This project demonstrates the addition of ten list elements with increasing font size when a "Start" button is clicked. It showcases basic HTML, CSS, and JavaScript concepts, such as DOM manipulation, event handling, and iteration.

## Installation

1. Download the project files to your local machine.

   git clone https://github.com/19Archmiel88/Adding-10-Elements-to-a-List.git

2. Open the `index.html` file in your preferred web browser.

## How to Use

1. Click the "Start" button to add ten list elements to the list.

   - Each element will be displayed with an increasing font size.

## Code Overview

The JavaScript code in `main.js` offers two methods to achieve the same result:

### Using a For Loop

1. When the "Start" button is clicked, the font size variable `fontSize` is incremented.

2. A loop iterates through each list item and checks if it's displayed (by checking its `style.display` property).

3. If an item is not displayed, it is set to be displayed.

4. All list items are displayed, and their font size is set to the current `fontSize`.

### Using `forEach` Method

1. When the "Start" button is clicked, the `forEach` method iterates through all list items.

2. Each list item is set to be displayed, and its font size is increased by the `fontSize` variable.

This project serves as an example of adding elements to a list and modifying their appearance based on user interaction.

## Changelog

- Version 1.0: Initial release

## Contributions

Feel free to contribute to this project by suggesting improvements or adding new features. Pull requests are welcome!
