Summary: 
The project explores building simulation algorithms of Swarm Robotics by leveraging ground robots and drones in an Agent-Based Model to improve yield optimization. The algorithms focus on:
efficiency and effectiveness in communication between the drones and ground robots
path planning, optimization, and coordination
weed detection in plants

The initial project proposal can be referenced by [Project Proposal - Robotics.pptx](https://github.com/bethunbhowmik/DGMD-E17_Swarm-Robotics/blob/main/Project%20Proposal%20-%20Robotics.pptx) and the corresponding video can be seen at [Project Proposal Video.mp4](https://github.com/bethunbhowmik/DGMD-E17_Swarm-Robotics/blob/main/Project%20Proposal%20Video.mp4) in this Github repository.

**Technology Used**:
Initially, we had planned to use Python MESA framework for agent-based modeling (ABM) as well as machine learning models. However, the team decided to switch to using Netlogo due to the platform’s ability to provide an integrated coding, visualization and analytics environment. 

**Environment Setup**:
We setup an initial environment in Netlogo with a light green farm background. Then we depicted plants in dark green color, weed in brown color, ground robots in blue, drones in yellow.
We have used an iterative and agile framework for coding. First, we achieved swarm behavior among the ground robots using Particle Swarm Optimization (PSO) algorithm logic. Then we added additional parameters that can be customized by the user such as population size of drones, weed probability, plant probability, search radius, number of drones, inertia of the robots. The search radius of the drones are 3 times the search radius of the ground robots. 

**Output**:
In the simulation the outputs tracked are number of weeds left (should be 0), active robots, and total energy consumed. We also plot the number of weeds over time. 

**Simulation**:
Please refer [Swarm_R1.4.nlogo](https://github.com/bethunbhowmik/DGMD-E17_Swarm-Robotics/blob/main/Swarm_R1.4.nlogo) for the simulation. You may need to download the Netlogo file and install Netlogo on your machine. The input parameters can be updated by the user on sliders. Once done, click on setup and then click on Go. The code for the simulation can be seen by clicing on the code tab in Netlogo.
The [demo video](https://github.com/bethunbhowmik/DGMD-E17_Swarm-Robotics/blob/main/Demo_Swarm%20Robotics.mp4) also gives an idea of the simulation progress through stages. 

**Analysis**:
We have run scanario analysis by using the Behavior Space tool in Netlogo. The raw data file running analysis on overall time and energy consumed by changing input parameters can be found [here](https://github.com/bethunbhowmik/DGMD-E17_Swarm-Robotics/blob/main/Swarm_R1.3%20experiment.csv).

**Ethical considerations**:
Ethical considerations we have documented as a team can be referred via [Ethics Presentation.pptx](https://github.com/bethunbhowmik/DGMD-E17_Swarm-Robotics/blob/main/Ethics%20Presentation.pptx)



