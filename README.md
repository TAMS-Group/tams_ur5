tams_ur5
======

This repository combines the ur5 arm with the robotiq s model gripper and the fts150 force torque sensor(not yet integrated).

---

__Usage__

To bring up the robot description and the necessary drivers run: 

```roslaunch tams_u5_bringup tams_ur5.launch```

Running the drivers seperately use:

```roslaunch tams_ur5_bringup tams_ur5_drivers.launch```

Uplouding the robot description seperately use:

```roslaunch tams_ur5_description tams_ur5_upload.launch```
