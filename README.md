tams_ur5
======

**Note: This package is deprecated, use https://github.com/TAMS-Group/tams_ur5_setup directly**
---

This repository combines the ur5 arm with the robotiq s model gripper and the fts150 force torque sensor(not yet integrated).

---

__Usage__

To bring up the robot description and the necessary drivers run: 

```roslaunch tams_u5_bringup tams_ur5.launch```

Running the drivers separately use:

```roslaunch tams_ur5_bringup tams_ur5_drivers.launch```

Uploading the robot description separately use:

```roslaunch tams_ur5_description tams_ur5_upload.launch```

---

__Usage in tams_ur5_setup__

This repo is used by [tams_ur5_setup](https://github.com/TAMS-Group/tams_ur5_setup) to embed the arm in the corner of the tams lab for the full tams setup.
