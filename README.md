# monty_hall_simulator
Simulation for monty hall problem
monty_hall_simultor(cycles, switch=False)
where cycles is an integer corresponding to the amount of cycles for the simulator to run, and switch is whether or not the contestant opts to switch doors
after the opening of the door to reveal a 'goat'. 1 cycle corresponds to 100 attempts at the monty hall problem.
Simulator returns an array the length of cycles, each value representing wins out of 100 cycles.
This data can be used to visualise the distribution of wins given a particular strategy of 'switch' of 'no switch' during the monty hall problem.
Execution and visualisation for both strategies is included below the function.
