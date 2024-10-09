# Diamond-Robot

The Diamond Robot is a specialized parallel robot designed for applications where precise control of the end-effector orientation is crucial.

<p align="center" width="100%">
    <img width="40%" src="images/delta2d.png">
    <img width="40%" src="images/realdiamondrobot.jpg">
</p>

### Content

In the `DiamondRobot.m` file you can find the robot **modelization**, **planning** and **control** using several techniques:
- Computed Torque
- Adaptive Computed Torque
- Backstepping
- Adaptive Backstepping
- Trace Control

The file `ScrewCalculusPro.m` contains a library used to obtain the robot kinematic and dynamic equations.

### Modelization

The robotics dynamic equations have been obtained through the **Denavit-Hartenberg** robot parameterization.

<p align="center" width="100%">
    <img width="40%" src="images/diamond.jpeg">
    <img width="40%" src="images/inkdiamond.jpg">
</p>


### Planning

The aim is to make the end-effector following this trajectory:

<p align="center" width="100%">
    <img width="30%" src="images/ref.jpeg">
</p>

### Control

This is a simulation of the control obtained using **Adaptive Backstepping**:

<p align="center" width="100%">
    <img src="https://github.com/user-attachments/assets/a84cba3c-edb6-4da7-b864-445a63c14d29">
</p>
