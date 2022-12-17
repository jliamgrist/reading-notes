# Class 12

## The Canvas Element

The `<canvas>` element allows you to draw 2D graphics using JavaScript. You can choose the height and width of the canvas element using the DOM methods or setting the properties throught the DOM window. 

Any content between the opening and closing tage can be fallback content, in cas the browser does not support the `<canvas>` element. 

You can use the `getContext() method to return a render context object which allows you to draw shapes, text, images, and other objects on the canvas. 

+ Use the getContext('2d') to get the 2D drawing context for drawing 2D graphics on canvas.
+ Use the fillStyle and StrokeStyle properties to set the styles for the 2D drawing context.

[javascripttutorial.net](https://www.javascripttutorial.net/web-apis/javascript-canvas/)

## Chart.js

Chart.js is a highly customizable library for building charts with JavaScript. It renders chart elements on an HTML5 canvas, and is much better than SVG rendering on your DOM tree. Chart examples you can build are an area chart, bar chart, bubble chart. You can construct the chart in your js file and ingect it to the canvas using DOM manipulation.

Chart.js can be used to make a website be more informative and visually interactive. 