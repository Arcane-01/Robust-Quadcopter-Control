# Robust-Quadcopter-Control
Code for the Coursera course on Aerial Robotics by University of Pennsylvania
## 1D control of Quadcopter
Implemented a PD controller for height control of the quadrotor and tuned the proportional gain( $K_p$ ) & derivative gain( $K_d$ ) for two cases.
### Hover control at height $0 m$
<img src="https://i.imgur.com/sjb3Hax.gif" width="600">


### Hover control at height $1 m$
<img src="https://i.imgur.com/hUNL5Cy.gif" width="600">

## 2D Control of Quadcopter
Implemented a PD controller to control the motion of the quadrotor in the Y-Z(2D) plane for following the desired path while minimising position error.

### Line Trajectory
<img src="https://i.imgur.com/RBx20Oo.gif" width="600">

### Sine Trajectory
<img src="https://i.imgur.com/alDXe4I.gif" width="600">

## 3D Control of Quadcopter
The aim is to design controller to track the given three dimensional trajectories while minimising the position error.

### Line Trajectory
<img src="https://i.imgur.com/IXZikkK.gif" width="600">

####                   Quadcopter velocity                                          Quadcopter position

<img src="https://i.imgur.com/giXTM5l.jpg" width="300"/> <img src="https://i.imgur.com/5B75MVU.jpg" width="300"/>

### Helix Trajectory

<img src="https://i.imgur.com/U2YcQ1g.gif" width="600">

####                   Quadcopter velocity                                          Quadcopter position

<img src="https://i.imgur.com/5pvjgz5.png" width="275"/> <img src="https://i.imgur.com/28oYnSH.jpg" width="275"/>

### Minimum Snap Trajectory through given waypoints
<img src="https://i.imgur.com/agvmTQC.gif" width="600">

####                   Quadcopter velocity                                          Quadcopter position

<img src="https://i.imgur.com/m5QtAeB.jpg" width="300"/> <img src="https://i.imgur.com/426y7HL.jpg" width="300"/>
