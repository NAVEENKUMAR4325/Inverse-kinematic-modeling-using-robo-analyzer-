# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:
1. open the roboanalyzer software.
2. select the robot and its degrees of freedom.
3. change the values of X and Y wherever necessary.
4. simulate the model for inverse kinematics.
5. plot the graph between the joints.
6. update the DH parameters of the link configuration and end effector configuration.








### SIMULATION 
 RPR:
 
 ![Rpr1](https://github.com/NAVEENKUMAR4325/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119479566/7fd31f74-d849-4786-9127-2a85a7ee4019)

 ![rpr2](https://github.com/NAVEENKUMAR4325/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119479566/0167f499-bc2b-48c7-9165-0fc0b3a4d07e)

 3R Robot
 
 ![3R 1](https://github.com/NAVEENKUMAR4325/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119479566/a0c18c36-d5fe-4258-9638-fbe0330a75ab)
 
 ![3r 2](https://github.com/NAVEENKUMAR4325/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119479566/ceef8341-03ed-4d76-8646-d20ab0060b67)


 
 
 
 
 ### PLOT:
 
 RPR Robot
 
 ![pl  rpr1](https://github.com/NAVEENKUMAR4325/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119479566/074b0c14-1b72-46d1-a9d3-d553c0264d33)
 
 ![pl rpr2](https://github.com/NAVEENKUMAR4325/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119479566/65d39f5f-ff14-4e11-a3e1-d931805cd656)
 
 3R Robot
 
 ![pl 3r1](https://github.com/NAVEENKUMAR4325/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119479566/015248fe-c0cc-4c85-87e4-747534192616)
 
 ![pl 3r2](https://github.com/NAVEENKUMAR4325/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119479566/d70f887a-0605-4486-8679-3a7354b05717)




 
 
 
 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  

Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
