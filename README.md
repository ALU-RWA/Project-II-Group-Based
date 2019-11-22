FORMATIVE ASSIGNMENT
Project II Group Based Assignment
Due: 28th Nov, 2019
Instructions: Choose one question from the questions set.

Write a program to simulate a simple Timer/StopWatch.
Guidelines:
It should display Hours, Minutes, Seconds
The timer should be implemented using Processes, Signals, Threads and Synchronization.
You are free to use any libraries that you know. You are also not limited to using Structs, Arrays, Pointers etc.
Make your program interactive search that the program if the user press S the Timer will start, if P the program will pause, and if press Esc the program will exit

Process - Use process to call the timer.
Thread - This will be several threads like for keyboard hit to start the timer.
Signals - To start the stopwatch and to stop the stopwatch.
Synchronization - To control the hours, Mins, Second count.
Struct - time status i.e. hours, mins, secs.


Write a program in C to simulate an elevator.
Guidelines:
The simulation is of people using the lift to arrive at their floor of a 8-story building. For the simulation we will expect people to start at floor 1 and exit at their destination. When all people have arrived at their floor, the simulation ends.
Passenger: 
1) 10 people will use the elevator (1 thread per person created at the start of simulation). 
2) Each person begins at floor 1 waiting for an elevator. 
3) Each person randomly picks a floor from 2 to 8. 
4) A person will wait for an elevator to arrive. 
5) A person will enter into the elevator only if there is room. 
6) A person will only board the elevator going to their floor. 
7) Once at the destination floor, the person exits the elevator. 
Elevators: 
1) There is only 1 elevator (1 thread for this elevator). 
2) Elevator can only hold 10 people. 
3) The elevator start on floor 1. 
4) Elevator thread sleep 1 second per floor to simulate travel time. 

Other Guidelines: 
1) Each activity of each thread should be printed to the screen. 



This is a group assignment. All members of the group should have a part to play in the completion of the task. Submit your work on Github
