# Calculator App

A single-page calculator interface built with HTML, inline CSS, and vanilla JavaScript. It presents a numeric keypad, decimal input, clear button, and arithmetic controls.

## Open the demo

Open `index.html` in a browser. There is no package installation or build step. The page loads Tailwind from a CDN, so its CDN styling requires an internet connection.

## Use and customize

Click digits to enter a number, choose an operator, enter the next number, and press **=**. **C** resets the display. All markup, styles, and event handlers live in `index.html`.

The implementation is a practice project. Multiplication currently displays the × symbol but the calculation switch expects `*`, so multiplication needs a code fix. Operator buttons also have both inline and registered click handlers; verify chained-operation behavior before relying on results. There are no automated tests.
