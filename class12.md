# Chart.js, Canvas

![charts](https://i.stack.imgur.com/vw0F2.png)

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.


**Craete line Charts**

1. create a canvas element in our HTML

`<canvas id="buyers" width="600" height="400"></canvas>`

2.  write a script that will retrieve the context of the canvas

`<script>`

    var buyers = document.getElementById('buyers')getContext('2d');
    new Chart(buyers).Line(buyerData);
`</script>`

3. we need to create our data in javascript 


`var buyerData = {`
	
    labels : ["January","February","March","April",
    "May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
`}`

**Drawing a pie chart**

1. we need the canvas element:

`<canvas id="countries" width="600" height="400"></canvas>`

2. we need to get the context and to instantiate the chart:

`var countries= document.getElementById("countries").getContext("2d");`

`new Chart(countries).Pie(pieData, pieOptions);`

3. create the data

`var pieData = [`
	
    {
		value: 20,
		color:"#878BB6"
	},
	{
		value : 40,
		color : "#4ACAB4"
	},
	{
		value : 10,
		color : "#FF8153"
	},
	{
		value : 30,
		color : "#FFEA88"
	}
`];`

4. add our options:

`var pieOptions = {`
	
    segmentShowStroke : false,
	animateScale : true
`}`

**Drawing a bar chart**

1. add the canvas element:

`<canvas id="income" width="600" height="400"></canvas>`

2. retrieve the element and create the graph:

`var income = document.getElementById("income").getContext("2d");`

`new Chart(income).Bar(barData);`

3. we add in the bar chart’s data:

`var barData = {`
	
    labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "#48A497",
			strokeColor : "#48A4D1",
			data : [456,479,324,569,702,600]
		},
		{
			fillColor : "rgba(73,188,170,0.4)",
			strokeColor : "rgba(72,174,209,0.4)",
			data : [364,504,605,400,345,320]
		}

	]
`}`

all information from [www.webdesignerdepot.com](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

-------------------------------------------------------

