# Blender world model
The ```.blend``` file contains the world mesh and can be used to generate ```.sdf``` files for the Gazebo actors.

## Scripts
To instruct the Gazebo actor and export a ground truth for further processing (e.g. Matlab), we provide the following Blender scripts:
- ```toActorSDF```:
adds to an existing sdf file the waypoints from the path generated in Blender

- ```toCSV```:
export the path to a CSV file (3D poses + Euler angles)

## Notes
As Gazebo interpolates the waypoint poses contained in the ```.csv``` file, unexpected behaviors might arise because of the Euler angle periodicity.  

