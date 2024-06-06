# POSIXAviationSimulationSystem
This system consists of the following entities (simulated as processes): 
● Plane (Each plane is a single-threaded process). Two types of planes are considered. 
○ Passenger plane: includes passengers, 5 cabin crew members and 2 pilots 
○ Cargo plane: includes only 2 pilots 
● Airport (Each airport is a multi-threaded process) 
● Air Traffic Controller (ATC) (This is a single-threaded process) 
● Passenger traveling on a specific passenger plane (Each passenger process is a child of the corresponding plane 
process and each passenger process is single-threaded) 
● Cleanup (This is a single-threaded process) 
