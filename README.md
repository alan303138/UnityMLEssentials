# UnityMLEssentials
Various examples of ml-agents while teaching concepts about it in my [YouTube Channel](https://www.youtube.com/c/dilmervalecillos)

Example Scenes: (New Demos In Progress)

**ParkingLot.unity** Demonstrates how to park a car with machine learning.
**ParkingLotAdvanced.unity** Demonstrates how to park a car with machine learning in a more advanced area.

**Config** used -> /Assets/Config/SelfParking.yaml

<img src="https://github.com/dilmerv/UnityMLEssentials/blob/master/docs/images/ParkingLot1.gif" width="300">

<img src="https://github.com/dilmerv/UnityMLEssentials/blob/master/docs/images/ParkingLot2.gif" width="300">

# usage:

## create new environment
`git clone  https://github.com/alan303138/UnityMLEssentials`  
`cd UnityMLEssentials`  
`conda env create -f environment.yml`  
`conda activate agent`  

## train 
`mlagents-learn .\Assets\Config\SelfParking.yaml  --run-id="test"`  

## resume  
`mlagents-learn .\Assets\Config\SelfParking.yaml  --run-id="test" --resume`  
## monitor 
`tensorboard --logdir .\path_to\results`  

[check it in youtube part1](https://www.youtube.com/watch?v=IcatcC9Rikk)
[check it in youtube part2](https://www.youtube.com/watch?v=k_JNyLoB8vg)
