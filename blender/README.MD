The .blend file contains the world mesh and it can be used to generate new actor .sdf file.

They can be found in the scripting window in blender.



# Blender Scripts
## toActorSDF
Starting from an actor sdf template (containing the sdf of the actor), it generates a new sdf file with the waypoints of the blender path.
Some adjustements may be needed to export a valid path.

## toCSV
This script is used to generate the ground truth CSV file


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

