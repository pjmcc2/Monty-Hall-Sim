# A simulation of the Monty Hall Problem! 

This notebook shows the results of any number of Monty Hall problems with any number of doors (within reason). 
The simulation is implemented by creating a Door object that contains information about what is behind the door and if it has been chosen
or not. Next, the monty_hall_problem object holds N Door objects, and has methods to follow the flow of the real problem.
First a player chooses from among the doors, then the doors not selected that hide a goat are opened. Lastly, the player has the chance
to swap doors to the final hidden door, or keep their original choice. With only three doors, this doesn't seem like a big deal
(despite being 2/3 vs 1/3 odds) but with 100 doors the choice seems more obvious. 
The statistics behind these are reflected in bar graphs that show the results with and without swapping. 
