# The-Nature-of-Code-Examples p5.js

This is the repository for example [p5.js](https://github.com/lmccart/p5.js/) code from [The Nature of Code book](http://natureofcode.com/).  If you are looking for the book's raw content (text, illustrations, images, CSS, etc.), have a look at [The Nature of Code repo](https://github.com/shiffman/The-Nature-of-Code).

The original [Processing](http://processing.org) examples [can be found here](https://github.com/shiffman/The-Nature-of-Code-Examples), along with a [list of other ports](https://github.com/shiffman/The-Nature-of-Code-Examples/blob/master/README.md).


## Installation Instruction

To run these examples you have to use a local server.

For more information on how to use a local server,Please visit following links.

[Local Server Guide](https://github.com/processing/p5.js/wiki/Local-server)

[p5.js Workflow](https://www.youtube.com/watch?v=HZ4D3wDRaec)

[Local Server,Text Editor,Console](https://www.youtube.com/watch?v=UCHzlUiDD10)


## Note

*I have specifically set the link attribute to "//" to support both http and https protocol while fetching p5.js library.This is intended and not a bug.*

# Notes Michel:
- The book: [The Nature of Code](https://natureofcode.com/introduction/)
- Use LivePreview plugin to show HTML live in editor.

## Setup

### 1) Create a folder with the following files:
    - `index.html`
    - `sketch.js`

### 2) Add this `html` code to the `index.html`:
```html
<!DOCTYPE html>
<html>

<head>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.1/p5.min.js"></script>
  <meta charset="utf-8" />
</head>

<body>
  <script src="sketch.js"></script>
</body>

</html>
```
## 3) And now start coding in the `sketch.js` file...
There are 2 main function you need:
```js
// Set up your screen and canvas
function setup() {
    createCanvas(640, 240);
    background(255);
}
  
// Draw something  
function draw() {
    fill(0, 25);
    stroke(0, 50);
    circle(random(width),random(height), 16)
}
```
