# Unity-Coordinates

Unity_coords.json contains the mapping between the room names and locations on the generated maps. 
The maps were generated using SLAM Toolbox. The Slam Toolbox package uses information from lidar scanner in the form of a LaserScan message and 
TF transforms from odom->base link, lidar->base_link, and creates a map 2D map of a space, publishing the odom->map transformation. 
