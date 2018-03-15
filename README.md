# robotics-project
A 6DOF UR3 robot simulation using V-REP

Checkpoint 1

We use V-REP as the simulation envrionment. Follow the instructions below:

1) You can download and install V-REP from this link here: http://www.coppeliarobotics.com/downloads.html

2) In order to run the code, you need to open up V-REP and import the UR3 robot into the scence. 

3) In the scence hierarchy, next to the UR3 object, double click the code icon and copy and paste the attached code.txt in the .zip folder as provided. 

4) Run the simulation by clicking on the triangle RUN button in V-REP. You should be able to see the robot arm moving as shown in the video: https://www.youtube.com/watch?v=Cu9Fpxxuqec


Checkpoint 2: Monday, March 12

For this checkpoint, we use Matlab to simulate Vrep. In order to this, you need to do two things.
First, in the vrep folder, go to /programming/remoteApiBindings/matlab, copy remoteApiProto.m and remApi to the directory that you want to write Matlab. 
Second, go to programming/remoteApiBindings/lib and copy this file remoteApi.dylib to the same directory as above. 
Now, you can use Matlib to simulate Vrep directly. 

In this checkpoint, we implement the Forward Kinematics using the method we discussed in class. In order to reproduce the result, you need to follow the instructions from the last checkpoint and paste the new code for this checkpoint from the .zip folder. After pasting the code, you can hit the run button and you can observe the robot arm moves to three different configurations with the destination frame highlighted. 
A video of this demo can be found in this link: https://www.youtube.com/watch?v=B5U-Nm_UTXE


Checkpoint 2: Tuesday, March 27

For this checkpoint, we implement the Inverse Kinematics of the UR3 in VREP. As a result, our robot can move to a series of positions as indicated by the user defined pose as well as random pose. In order to reproduce the result, you need to follow the instructions below:

1) Open V-REP and drag a UR3 robot in the scene

2) Paste the new code in the .ZIP folder to the script of UR3 robot

3) Hit the RUN button in V-REP and you can see the robot arm moving as shown in the video: 










