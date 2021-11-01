# Roid1 URDF

This is a URDF file of a small humanoid robot Roid1 and it's Rviz operation demo.
You can operate the joints of the robot with sliders.


# Usage

This demo has been confirmed to work on ROS-melodic with Rviz.

$ cd ~/catkin_ws/src/

$ git clone https://github.com/Ninagawa123/roid1_urdf.git

$ cd ~/catkin_ws/

$ catkin build

$ roslaunch roid1_urdf display.launch


# Directory Tree

<pre>
~/catkin_ws/src/
└── roid1_urdf #ros_package
    ├── CMakeLists.txt
    ├── package.xml
    ├── LICENSE
    ├── readme.md
    ├── launch
    │   └── display.launch
    └── urdf
        ├── c_chest_a.stl
        ├── c_chest_b.stl
        ├── c_head_a.stl
        ├── c_head_b.stl
        ├── c_waist.stl
        ├── l_ankle.stl
        ├── l_elbow.stl
        ├── l_foot.stl
        ├── l_hipjointlower.stl
        ├── l_hipjointupper.stl
        ├── l_hipjointupperpoint.stl
        ├── l_lowerarm.stl
        ├── l_lowerreg_a.stl
        ├── l_lowerreg_b.stl
        ├── l_shoulder.stl
        ├── l_upperarm.stl
        ├── l_upperreg_a.stl
        ├── l_upperreg_b.stl
        ├── shoulderpoint.stl
        ├── r_ankle.stl
        ├── r_elbow.stl
        ├── r_foot.stl
        ├── r_hipjointlower.stl
        ├── r_hipjointupper.stl
        ├── r_hipjointupperpoint.stl
        ├── r_lowerarm.stl
        ├── r_lowerreg_a.stl
        ├── r_lowerreg_b.stl
        ├── r_shoulder.stl
        ├── r_upperarm.stl
        ├── r_upperreg_a.stl
        ├── r_upperreg_b.stl
        ├── roid1.urdf
        └── urdf.rviz
</pre>
