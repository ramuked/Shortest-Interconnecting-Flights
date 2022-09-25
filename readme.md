## Shortest Interconnecting Flights

Using dataset provided on kaggle : https://www.kaggle.com/datasets/flashgordon/usa-airport-dataset, I was able to find out shortest interconnecting flights between two cities. 

Describing the graph:
Here various cities are treated as vertices, with a flight from city A to city B acting as a directeed edge between the cities.
The distance between the two cities is considered as the weight of edge.
Using Dijkstra's algorithm, the shortest sequence of interconnected flight can be determined. 

A reservation system has also been created, to simulate the experience of booking flight tickets.

