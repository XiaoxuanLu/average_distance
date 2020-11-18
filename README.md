# Average_distance
A program that makes a graph with the number 
of dimensions on the horizontal axis using a logarithmic scale and the average distance between two points in an n-dimensional unit hypercube on the vertical axis. Your graph should be the result of generating a number of such pairs of points and averaging over the distances between them.

## Table of contents
* [Functions](#functions)
* [Technologies](#technologies)
* [Plot](#plot)
* [Result](#result)

## Functions
#### dis(lst_coords)
The function takes a list of coordinates, and return a list of distances between any two points in the input.
The function uses combinations in itertools to readily combine any two points in a list.

####  ave(lst)
The function takes a list of distances, and return the average distance of the list.
####  generate(n, p)
The function generates a list of random points. P is the number of the points in the list, and n is the 
number of dimension. For example, if we set n = 3, p = 2. Any number in coordinates
should be between 0 to 1.
####  plot(n, p)
This is the main function to plot the graph. The function plots  a graph with the number 
of dimensions on the horizontal axis using a logarithmic scale and the average distance between 
two points in an n-dimensional unit hypercube. n is the max number of dimension we want to draw,
and p is the number of random points we want to generate in each dimension. 
	
## Technologies
Project is created with:
* Jupyter notebook: average_distance.ipynb
* Python: 3

	
## Plot
To plot the graph, run:

```
$ plot(n, p)
n, p are both positive integer
```
In the program, I run plot(1000, 100) and plot(10000, 100).
I set the random points generated for each dimension as 100.

## Result
 ![1000_100](https://git.auc-computing.nl/XiaoxuanLu/Average_distances/src/branch/master/1000_100.png)
