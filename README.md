#  Cheat Sheet D3.js
Welcome! This a Data Science repository.

## Description

Adrian's cheat sheet for [D3.js](https://d3js.org/). This repository pretend to be two things:

* A quick reference to the basics of _D3.js_
* A page to evolve the main things of the library 

Let´s start 🚀

## Table of contents
- Basic information
    - [Prerequisites](#Prerequisites)
    - [What is _D3.js_](#what)
- [Selections](#selections)
- [Classes](#)
- [Link/Href](#)


#### Prerequisites

* You are familiar with HTML, the DOM, and CSS
* Have a little programming experience already
* Aren’t scared by unknown initialisms like CSV, SVG, or JSON
  

#### 📝 What is _D3.js_? 


<a href="https://d3js.org"><img src="https://d3js.org/logo.svg" align="left" hspace="5" vspace="6"></a>
The D3 library (abbreviation of **Data Driven Documents**) is a library written in Javascript that allows the inclusion of graphs and visualizations of data in any standard web page. For further and detailed information visit D3.js github [here](https://github.com/d3/d3).
 

## Selections

| Command        | Explanation      | Example  |
|:-------------:|:-------------:|:-----:|
| d3.select()      | Returns the element found |  d3.select("svg") |
| d3.selectAll()      | Returns all found elements      |    d3.selectAll("circle") |
| selection.append() | Creates a new element inside the selection      |   d3.select("svg").append("circle") |


## Attributes/Styles - initialization
```javascript
var svgWrapper = d3.select("body")
  .append("svg")
  .attr("id", "viz")
  .attr("width", width + margin.left + margin.right)
  .attr("height", height + margin.top + margin.bottom);

var container = svgWrapper.append("g")
  .attr("transform", "translate(" + margin.left + "," + margin.top + ")")
  .style("pointer-events", "all");
```


## Examples

There is a folder  call _Examples📂_ inside you can see some of cases that I used to try the library.

⚠️ Please if you have any problems installing visit the D3.js github [here](https://github.com/d3/d3).

## Authors

* **Adrián**  👨🏻‍💻
  
- [x] Feel free to contribute

## Contributors

This page was inspired by [Scott Murray](https://github.com/alignedleft)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Copyright (c) 2018 Adrián.

