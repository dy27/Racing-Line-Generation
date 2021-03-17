# racing-line-generation
 \* DOCUMENTATION IN PROGRESS *
 
This program reads in a list of waypoints of a racing track and the track width at each waypoint, and generates an approximation of an optimal racing line based on a node traversal algorithm. The algorithm minimises a combination of two parameters: shortest distance and minimal angle change. Each parameter has its own weight, which can be calibrated for better results.

The algorithm used does not reflect a true racing line, though it may be able to generate a decent approximation.

As of now, the program is not functioning perfectly, the algorithm seems to make poor node choices in many circumstances. Refer to the included image for an example of a generated line. It seems to be quite far from what a racing line should look like.
