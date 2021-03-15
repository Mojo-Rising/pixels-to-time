# Assignment: Pixels to time

*PLEASE READ THIS **ENTIRE** DOCUMENT FIRST*

* [the assignment](#the-assignment)
* [submitting-your-work](#submitting-your-work)


## The assignment

(Screenshot_2021-03-15 Crypto Compare.png)

Download this repo and edit the `index.html`.

* Run the index with the live server and inspect the console as you hover over the line in the svg.
* Read the code and comments carefully
* As you can see, a tooltip has already been made:

`
let tooltip = d3.select("#my_dataviz")
                .append("div")
                .style("opacity", 0)
                .attr("class", "tooltip");
`

* Using the mouseout, mouseover and mousemove events, activate the tooltip only when the line is hovered over. 
* Display the local coordinates of the graph in the tooltip
* Using the local x coordinate, find a way to get the date associated with that our x coordinate and our scale and display it in the tooltip
* Finally, add a thin vertical line at the mouseposition that goes from `y1: 0` to `y2: height`. This will help add context to our tooltip.



## Submitting your work
Create a new branch called **gh-pages** and upload your local work into this branch. Submit a new **pull request** and make sure to put the (working) **GitHub Pages URL** in the comment section. 
