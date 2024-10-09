## Laboratory 1
I've used the tweak and fitness function the professor used in the lesson. 

The algorithm I've chosen is Tabu search. So the algorithm will explore different solutions using the tweak function, but will avoid cycles through the tabu list, implemented as a deque. The size of the list can be modified. I've also inserted max iterations as a parameter since instances 4, 5 and 6 require a lot of time to run. 

Noticing that Tabu search was struggling with some instances, I've decided to try with simulated annealing and see if it worked better. The initial temperature, cooling rate and minimum temperature are global variables.

From what I've seen Tabu search generally finds better results, with Simulated Annealing outperforming it only in the first instance. 