# Element of Biology - Ant Colony-Based Algorithms

## Project Description
This project focuses on **Ant Colony-Based Algorithms** and their application to **Antivirus Software Optimization**.

## SAP ID
- **ID**: 70572500133
- **ID**: 70572500134
- **ID**: 70572500136

## Technologies Used
- HTML5
- CSS3
- JavaScript

## Flowchart
START
  ↓
Load Web Page
  ↓
Display Intro Page
  ↓
[User clicks "Launch Simulation"?]
        ↓ Yes
Hide Intro Page
Show Simulation UI
  ↓
Initialize Grid & Parameters
  ↓
Wait for User Action
User clicks "Start Simulation"
  ↓
Is Simulation Already Running?
  ├─ Yes → Pause Simulation
  └─ No
        ↓
Initialize Grid
Initialize Pheromone Matrix
Place Virus Files
Create Ant Agents
Set Start Time
Iteration = 0
  ↓
Start Simulation Loop
SIMULATION LOOP (requestAnimationFrame)
  ↓
For each Ant
  ↓
Is Ant Alive?
  ├─ No → Skip Ant
  └─ Yes
        ↓
Find Neighbor Cells
        ↓
Calculate Probabilities
(Pheromone + Distance Heuristic)
        ↓
Select Next Cell (Roulette Wheel)
        ↓
Move Ant
        ↓
Add Cell to Path
        ↓
Check for Virus
        ├─ Virus Found?
        │     ├─ Yes
        │     │     ↓
        │     │ Mark Virus Found
        │     │ Update Best Path
        │     │ Deposit Pheromone
        │     └─ No
        ↓
Check Path Length Limit
        ↓
Continue
Are All Ants Dead?
  ├─ No → Continue Simulation Loop
  └─ Yes
        ↓
Iteration++
Evaporate Pheromones
        ↓
Have All Viruses Been Found?
        ├─ No → Create New Ants
        │         ↓
        │      Continue Loop
        └─ Yes
              ↓
Have Enough Iterations Passed?
        ├─ No → Create New Ants
        │         ↓
        │      Continue Loop
        └─ Yes
              ↓
Stop Simulation
Display Results
Simulation Complete
  ↓
Highlight Optimized Paths
  ↓
Display:
- Shortest Path Length
- Virus-wise Best Paths
- Time Elapsed
- Iterations Count
  ↓
Wait for User:
[Reset] or [Change Parameters]
User Clicks Reset OR Changes Grid Size
  ↓
Stop Simulation
  ↓
Clear Ants
Clear Pheromones
Clear Paths
  ↓
Reinitialize Grid
  ↓
Ready to Start Again

##WEB PAGE URL
https://aanumeeeet.github.io/Element_of_Biology_70572500133/
