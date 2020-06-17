# MarsSim
Planetary-like environment in ROS Gazebo + Blender

Tested on **Ubuntu 16.04** & **Gazebo 8**

![alt-text-1](imgs/intro_pic.png "Environment & Rendered View" | height=400) ![alt-text-2](legoloam.png "Map & Trajectory from LeGO-LOAM" | height=400)

### Environments
```world.launch```: spawn world generated from cropped martian DTM + added populations of rocks of various size
```actor_long.launch```: spawn world and box with stereocamera and 3D LiDAR moving on a fixed closed path of ~300 meters
```actor_long_rocks.launch```: as before, but this time more rocks are present, some of them are big boulders
```actor_short.launch```: spawn world and box with stereocamera and 3D LiDAR moving on a short path of ~60 meters

# References
This simulated environment is used in "Simulation Framework for Mobile Robots in Planetary-Like Environments", in IEEE International Workshop on Metrology for Aerospace, 2020. If you find it useful for your projects and research, consider to cite our paper using the following BibTeX:
```
@INPROCEEDINGS{giubilato2020simulation,
  author    = {R. Giubilato and A. Masili and S. Chiodini and 
               M. Pertile and S. Debei},
  booktitle = {2020 IEEE 7th International Workshop on Metrology 
               for AeroSpace (MetroAeroSpace)}, 
  title     = {Simulation Framework for Mobile Robots in 
               Planetary-Like Environments}, 
  year      = {2020},
}
```
