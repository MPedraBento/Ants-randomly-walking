# Ants-randomly-walking
Solutions to a problem proposed by Optiver:

An ant leaves its anthill in order to forage for food. It moves with the speed of 1 step per second, but it doesn’t know where to go, therefore every second it moves randomly 1 step directly north, south, east or west with equal probability.

Q1: If the food is located on east-west lines 2 steps to the north and 2 steps to the south, as well as on north-south lines 2 steps to the east and 2 steps to the west from the anthill, how long will it take the ant to reach it on average?

Q2: What is the average time the ant will reach food if it is located only on a diagonal line defined with $y = 1 - x$?

Q3: Can you write a program that comes up with an estimate of average time to find food for any closed boundary around the anthill? What would be the answer if food is located outside an area defined by $( (x – 0.25) / 3 )^2 + ( (y – 0.25) / 4 )^2 < 1$ in coordinate system where the anthill is located at $(x = 0, y = 0)$?

-----------------

The answers using an absorbing Markov chain:

* Q1: 4.5

* Q2: Infinite

* Q3: Around 13.992
