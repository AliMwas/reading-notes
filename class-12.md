# Chart.js & Canvas

## Chart.js
How to Use Chart.js?
Chart.js is easy to use.

First, add a link to the providing CDN (Content Delivery Network):

< script
src =" ttps://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.9.4/Chart.js" >
</ script>
Then, add a < canvas> to where you want to draw the chart:

< canvas id="myChart" style="width:100%;max-width:700px"></ canvas>
The canvas element must have a unique id.

That's all!

Typical Scatter Chart Syntax:

var myChart = new Chart("myChart", {

  type: "scatter",

  data: {},

  options: {}

});

Typical Line Chart Syntax:

var myChart = new Chart("myChart", {

  type: "line",

  data: {},

  options: {}

});

Typical Bar Chart Syntax:

var myChart = new Chart("myChart", {

  type: "bar",

  data: {},

  options: {}

});

Drawing a pie chart
Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:

< canvas id="one" width="300" height="200"></ canvas>

## HTML Canvas Reference
The HTML < canvas> tag is used to draw graphics, on the fly, via scripting (usually JavaScript).

The < canvas> element
< canvas id="tutorial" width="200" height="200"></ canvas>
Copy to Clipboard
At first sight a < canvas> looks like the < img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the < canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 200 pixels wide and 200 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

![canvas](https://www.webfx.com/blog/images/assets/images.sixrevisions.com/2010/10/03-01_html5_canvas_element_ld_img.png)