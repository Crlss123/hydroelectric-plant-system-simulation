# hydroelectric-plant-system-simulation

This C++ project simulates the management of a hydroelectric plant system, where users can monitor workers, track the status of different plants, and calculate each plant's contribution to the overall electrical output. The simulation provides insights into the plant's operational efficiency and helps manage the workforce effectively.

Table of Contents
Features
System Requirements
Installation
Usage
Project Structure
Contributing
License
Features
Real-time monitoring: Track the status of individual workers and their tasks in each plant.
Plant monitoring: View the operational status of each hydroelectric plant in the system.
Power calculation: Automatically compute the electrical contribution of each plant to the grid.
Scalable system: Add multiple plants and workers for simulation purposes.
User-friendly interface: Easy-to-use text-based interface for interacting with the system.
System Requirements
C++11 or later
GCC or Clang compiler
A terminal to run the simulation
Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/Crlss123/hydroelectric-plant-system-simulation.git
Navigate to the project directory:

bash
Copy code
cd hydroelectric-plant-system-simulation
Compile the source code using a C++ compiler (GCC in this case):

bash
Copy code
g++ -std=c++11 -o hydroelectric_plant_simulation main.cpp
Run the simulation:

bash
Copy code
./hydroelectric_plant_simulation
Usage
Upon running the program, you'll be presented with a menu to manage workers and plants. The user can:

Add plants: Add new hydroelectric plants to the system.
Monitor workers: Assign tasks and track the status of workers in each plant.
View plant status: Display the operational status of the plants in the system.
Calculate total power: Get the total electrical output from all the plants in the system.
Example
bash
Copy code
Welcome to the Hydroelectric Plant Simulation System!
Please choose an option:
1. Add Plant
2. View Plant Status
3. Assign Worker Task
4. Calculate Total Power
5. Exit
