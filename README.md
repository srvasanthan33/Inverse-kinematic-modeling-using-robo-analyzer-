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
1. Open the RoboAnalyzer App:
![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/e5bb8915-894c-4b5f-bd1e-430a51a49b57)
2. Change the DOF to threee:
![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/87f0a2b9-ac10-4d80-bdda-4782a5d36eed)
3. Open Ikin:
![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/c384773b-da2c-4d27-9414-e6684d305bce)
4. Set Parameters:
![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/8679da68-62b9-44d7-a9df-7d8e32626023)
5.Click Fkin and play:
![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/9dda2f0b-6582-41dd-961c-00cf0eef07f4)








### SIMULATION 
 
 ![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/0ab66b0c-5105-4904-995b-41145411d70f)

 
 
 
 
 
 ### PLOT 
 
 
 Link 1:
 ![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/d3474ea7-b3c8-46ff-a4b7-1324bd2c59e6)
 Link 2:
 ![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/d5fa73ab-c9bb-48b9-9a7c-ba7824cbae3b)
Link 3:
![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/38a0bbca-25f6-4a3e-92c4-af8ece297f42)

Joints :
Joint 1:
![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/71aadf80-92e7-4c77-b4be-e0c9859ac69a)
Joint 2:
![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/db075b5b-5488-49e1-95b5-0dd8c2375958)

Joint 3:
![image](https://github.com/srvasanthan33/Inverse-kinematic-modeling-using-robo-analyzer-/assets/102546622/41023660-4cab-49a8-adf7-d2ed6f6c93ab)

### RESULTS :  
The inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position has been analyzed
