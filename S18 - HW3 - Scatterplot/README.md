**CS 725/825 - Spring 2018 - Homework 3 - Scatterplot**
Kavyashree Sirigere Prakash

__Scatterplot__   
1. What is the type of mark used in the scatterplot?   
*Point* is the mark type in Scatterplot

2. List the channels, the attribute they are mapped to, and the data type of that attribute.   
Channels used in Scatterplot are:   
 * Vertical spatial position   
 * Horizontal spatial position      
 
 *Number of Passing Touch Down's of player* is the quantitative attribute mapped on to vertical spatial position   
 *Number of Rushing Touch Down's for a player* is the quantitative attribute mapped on to horizontal spatial position

3. After your changes, list the channels, the attribute they are mapped to, and the data type of that attribute.   
 Another attribute that I considered is *Rushing Average*   
 Channels in Scatterplot are:  
 * Vertical spatial position   
 * Horizontal spatial position
 * Hue
 * Size

 *Number of Passing Touch Down's of player* is the quantitative attribute mapped on to vertical spatial position.   
 *Number of Rushing Touch Down's for a player* is the quantitative attribute mapped on to horizontal spatial position.
 
 *The player's conference* is a categorical attribute which is  expressed in Hue channel.
 *Rushing Average* is a quantitative attribute which is expressed in Size channel.
 
 Added Thumbnail of scatterplot   
__Extra Credit__
* I followed few blogs which explained about legend in D3.
* I am appending legend tag in vertical alignment
* Added "Conferences" label for the color legend
* To lable the colors,i created an array which stores names of all confeerences in dataset
* Then I used conditional loop to get colors for various conferences in a rectangale SVG
* Altered height,width and size of SVG to position towards left,vertically


__References__
 
* http://www.competa.com/blog/d3-js-part-7-of-9-adding-a-legend-to-explain-the-data/
* https://bl.ocks.org/zanarmstrong/0b6276e033142ce95f7f374e20f1c1a7
* http://d3-legend.susielu.com/#color-ordinal
* http://bl.ocks.org/juan-cb/ac731adaeadd3e855d26 -I found out that, this example was very helpful
































----------------------------------------------------------------------------------------------------------
See the assignment instructions at http://www.cs.odu.edu/~mweigle/CS725-S18/HW3

Scatterplot of 2014 NCAA Passing Statistics

Data from http://www.sports-reference.com/cfb/years/2014-passing.html

Scatterplot based on http://bl.ocks.org/mbostock/3887118, tooltip example from http://www.d3noob.org/2013/01/adding-tooltips-to-d3js-graph.html

Built with [blockbuilder.org](http://blockbuilder.org)

forked from <a href='http://bl.ocks.org/weiglemc/'>weiglemc</a>'s block: <a href='http://bl.ocks.org/weiglemc/703997367b85521e76d3fdd64c3c7b5f'>S18 - HW3 - Scatterplot</a>