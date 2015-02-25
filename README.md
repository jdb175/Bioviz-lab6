# Lab 6: Force-Directed Layouts

My initial strategy for setting the values was to just copy the [force-directed graph tutorial](http://bl.ocks.org/mbostock/4062045), which had a more distributed appearance than the reference. In particular the large center-right group was much less pronounced. Decreasing the charge value improved it somewhat, although tweaking never really gave me the exact thing I was looking for.

* Decreasing the charge value made the nodes spread out more, due to greater repulsion. Making the charge value positive just caused the whole thing to coalesce into a ball.
* Changing the link distance also changed how far the nodes tended to spread.
* I played with the charge distance, which when I added it compressed the graph significantly.


Based on Jordan's suggestion I added the ability to pin nodes, which can be done by double-clicking them. This allowed me to massage the graph to be a little more similar to the one in the reference, although it was still difficult to compare.