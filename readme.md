Jon Sorrells, cs 4802 lab 6  

To view the output, go to http://jlsorrells.github.io/cs4802l6/  

In the force directed layout, I set the charge to -60, the linkDistance to 20, and the gravity to 0.2.  
I set the charge to be high enough that the nodes in the large clusters have some space between them, but not so high that the layout is overly spread out.  
The link distance of 20 was chosen so that the smaller groups of nodes (ie the disconnected ones) were reasonable sizes.  
The gravity was increased to 0.2 so that the disconnected groups wouldn't fly off the screen, which they sometimes did at 0.1 gravity.  

The general shape of the graph is similar in my results and Bandyopadhyay et al.'s, but there are some differences.  
Their results have the nodes spread out more evenly in circles, whereas in my graph, the clusters of nodes all connected to a central node tend to fan out in one direction instead of forming a circle.  
Their graph has placed the disconnected groups all together and oriented the same way.  In my graph, the disconnected groups end up spread out along the outside of the graph.  
