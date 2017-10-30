# Javascript

- __[Framework](url)__ - an application skeleton. It requires you to approach software design in a specific way and insert your own logic at certain points.
- __[Library](url)__ - a javascript file that contains a bunch of functions which accomplish a task in a webpage.
<p align="center">
  <img src="https://www.programcreek.com/wp-content/uploads/2011/09/framework-vs-library.png">
</p>

## [Library](tps://www.javascripting.com/)

<p align="center">
  <img width="460" height="300" src="https://avatars1.githubusercontent.com/u/451160?v=4&s=200">
</p>

<center>

| FusionCharts        | javascript charting library; 90 Chart types and 100 maps   |
| ------------------  | :---------------------------------------------------------:|
| Website             |  http://www.fusioncharts.com/   		  	   |
| Repository          |  https://github.com/fusioncharts     		           |
| current version     |  3.12.1					   		   |

</center>

### Code Sample
[View Demo](http://jsfiddle.net/fusioncharts/x5FBh/)
```
FusionCharts.ready(function () {
    var salesChart = new FusionCharts({
        type: 'area2d',
        renderAt: 'chart-container',
        width: '400',
        height: '300',
        dataFormat: 'json',
        dataSource: {
            "chart": {
                "caption": "Sales of Liquor",
                "subCaption": "Last week",
                "xAxisName": "Day",
                "yAxisName": "Sales (In USD)",
                "numberPrefix": "$",
                "paletteColors": "#0075c2",
                "bgColor": "#ffffff",
                "showBorder": "0",
                "showCanvasBorder": "0",
                "plotBorderAlpha": "10",
                "usePlotGradientColor": "0",
                "plotFillAlpha": "50",
                "showXAxisLine": "1",
                "axisLineAlpha": "25",
                "divLineAlpha": "10",
                "showValues": "1",
                "showAlternateHGridColor": "0",
                "captionFontSize": "14",
                "subcaptionFontSize": "14",
                "subcaptionFontBold": "0",
                "toolTipColor": "#ffffff",
                "toolTipBorderThickness": "0",
                "toolTipBgColor": "#000000",
                "toolTipBgAlpha": "80",
                "toolTipBorderRadius": "2",
                "toolTipPadding": "5"
            },

            "data": [
                {
                    "label": "Mon",
                    "value": "4123"
                },
                {
                    "label": "Tue",
                    "value": "4633"
                },
                {
                    "label": "Wed",
                    "value": "5507"
                },
                {
                    "label": "Thu",
                    "value": "4910"
                },
                {
                    "label": "Fri",
                    "value": "5529"
                },
                {
                    "label": "Sat",
                    "value": "5803"
                },
                {
                    "label": "Sun",
                    "value": "6202"
                }
            ]
        }
    })
    .render();
});
```

<h1 align="center"> Bounce.js </h1>

<p align = "center">

| Bounce.js           | CSS3-powered animations comes with 10 pre-sets		   |
| ------------------  | :---------------------------------------------------------:|
| Website             |  http://bouncejs.com/		   		  	   |
| Repository          |  https://github.com/tictail/bounce.js  		           |
| rating	      |  67%					   		   |

</p>

### Installation
```
$ bower install bounce.js
# OR
$ npm install bounce.js
```

### Code Sample
[View Demo](http://bouncejs.com/)
```
var bounce = new Bounce();
bounce.scale({
  from: { x: 0.5, y: 0.5 },
  to: { x: 1, y: 1 }
});

```
<p align="center">
  <img width="460" height="300" src="https://avatars2.githubusercontent.com/u/8068250?v=4&s=200">
</p>

<center>

| Handsontable        | spreadsheet library for building web applications	   |
| ------------------  | :---------------------------------------------------------:|
| Website             |  https://handsontable.com/	   		  	   |
| Repository          |  https://github.com/handsontable/handsontable	           |
| rating	      |  67%					   		   |

</center>

### Code Sample
[View Demo](http://jsfiddle.net/handsoncode/s6t768pq/)

```
var data = function () {
  return Handsontable.helper.createSpreadsheetData(100, 10);
};

var container = document.getElementById('example');

var hot = new Handsontable(container, {
  data: data(),
  minSpareCols: 1,
  minSpareRows: 1,
  rowHeaders: true,
  colHeaders: true,
  contextMenu: true
});
```
### RESOURCES

https://www.sitepoint.com/3-javascript-libraries-2017/

https://www.youtube.com/watch?v=_vL8s5ayuFk

https://www.webdesignerdepot.com/2016/11/12-javascript-libraries-to-watch-in-2017/
