# Notes-on-CSS-Grid-Garden
[CSS Grid Garden](https://cssgridgarden.com/) is an interactive way to learn CSS Grid. So, This is my notes and solutions.

```grid-column-start``` add a integer value to set the object on the vertical border. SO, ```grid-column-start: 3;``` is 3rd grid from the top left side.

```grid-column-end``` allows you to span the object across mulitple grids. So with start and an end you have a range of grids you can cover. So if you want to start at 1 and end at 3, you have to put in 4 in the grid-column-end. It is not like the start value have to be small and the end value have to be larger. It can be the opposite too. 

The start and end can also take in negative values. So for the end, **-1** is the last grid and for start **-2** is the last grid.

Rather than giving a value as in the grid number in the grid-column-end you can define a value for how many grids it will span. So, it can be ```grid-column-end: span 2```. So span in the end forwardly covers, and span in start backwardly covers.

```grid-column``` combines both the ```grid-column-start``` and ```grid-column-end``` in a single property with slash in between them. So the syntax is ```grid-column: {start value} / {end value};``` so, ```grid-column: 2 / 4;``` And this property can also take in span values.


```grid-row-start``` 



