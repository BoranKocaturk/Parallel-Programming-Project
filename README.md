This project estimates Pi using the Monte Carlo Simulation method. Random points are generated within a unit square, and the number of points falling inside the quarter circle is counted to approximate the value of Pi. The number of points (samples) is defined by the user for flexible accuracy.

How It Works:

User specifies the number of random points to generate.

Each point is randomly placed inside a unit square (from (0,0) to (1,1)).

For each point, we check if it falls inside the quarter circle of radius 1 centered at (0,0).

Pi is estimated using the ratio of points inside the quarter circle to the total number of points.

Usage:

Run the script

python monte_carlo_pi.py

Example Output:

Enter number of points: 10000
Estimated Pi: 3.1412

Requirements:

Python 3.x

No additional libraries are required.
