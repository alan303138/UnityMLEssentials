# UnityMLEssentials
Various examples of ml-agents while teaching concepts about it in my [YouTube Channel](https://www.youtube.com/c/dilmervalecillos)

Example Scenes: (New Demos In Progress)

**ParkingLot.unity** Demonstrates how to park a car with machine learning.
**ParkingLotAdvanced.unity** Demonstrates how to park a car with machine learning in a more advanced area.

**Config** used -> /Assets/Config/SelfParking.yaml

<img src="https://github.com/dilmerv/UnityMLEssentials/blob/master/docs/images/ParkingLot1.gif" width="300">

<img src="https://github.com/dilmerv/UnityMLEssentials/blob/master/docs/images/ParkingLot2.gif" width="300">


**CrossTheRoad.unity** Demonstrates how to mimic Crossy Road game mechanic with machine learning.

**CrossTheRoad.unity** Demonstrates how to mimic Crossy Road game mechanic with machine learning.

**Config** used -> /Assets/Config/CrossTheRoad.yaml

<img src="https://github.com/dilmerv/UnityMLEssentials/blob/master/docs/images/CrossTheRoad1.gif" width="300">

<img src="https://github.com/dilmerv/UnityMLEssentials/blob/master/docs/images/CrossTheRoad2.gif" width="300">

<img src="https://github.com/dilmerv/UnityMLEssentials/blob/master/docs/images/CrossTheRoad3.gif" width="300">

**BasicPathFinding.unity** Demonstrates how agents learn to reach a goal and walk through an area.

**Config** used -> /Assets/Config/PlayerMaze.yaml

<img src="https://github.com/dilmerv/UnityMLEssentials/blob/master/docs/images/BasicPathFinding.gif" width="300">

**BasicAvoidance.unity** Demonstrates how agents learn to avoid objects coming towards them.

**Config** used -> /Assets/Config/PlayerAvoidance.yaml

<img src="https://github.com/dilmerv/UnityMLEssentials/blob/master/docs/images/BasicAvoidance.gif" width="300">
# usage:

## create new environment
`conda env create -f /path_to/environment.yml`  
`conda activate agent`  
`git clone https://github.com/dilmerv/UnityMLEssentials.git`  
`cd .\path_to\UnityMLEssentials`  
## train 
`mlagents-learn .\Assets\Config\SelfParking.yaml  --run-id= "test"`  

## resume  
`mlagents-learn .\Assets\Config\SelfParking.yaml  --run-id="test" --resume`  
## monitor 
`tensorboard --logdir .\path_to\results`  

[check it in youtube part1](https://www.youtube.com/watch?v=IcatcC9Rikk)
[check it in youtube part2](https://www.youtube.com/watch?v=k_JNyLoB8vg)
