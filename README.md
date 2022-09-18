<h1 align="center">
  <br>
Getting to Grips with Model-Free Deep Reinforcement Learning for Dexterous Robotic Manipulation: Challenges, Analysis, Limitations
  <br>
 </h1>
 

## Materials  
In order to have an exact replication of the robot used in this proposal, you will need the following materials:

|Material      | Brand| Quantity|
|--------------|------|---------|
| ServoMotors  | Dynamixel XL-320| 4  |
| WebCam  | Standard| 1  |
| STL Files  |   | [link](https://github.com/dvalenciar/td3_ddpg_translation_rotation/tree/main/STL_FILES_FOR_3D_PRINTER)   |
| USD2 PHB|Dynamixel | 1 |
| U2D2 INT|Dynamixel | 1 |
 
 ![](https://github.com/dvalenciar/td3_ddpg_translation_rotation/blob/main/images/gripper_full.png)

## State-Space
Two state-space representations were used as state input for all the algorithms. Image represention and vector representation

## Action-Space
The action-space controls the joint angles of each servomotors

## Results
For testing purposes, this robot is trained to complete a manipulation task, translation of an object (5cm cube).

![](https://github.com/dvalenciar/td3_ddpg_translation_rotation/blob/main/images/gripper_new.png)

Results using image representation
![](https://github.com/dvalenciar/td3_ddpg_translation_rotation/blob/main/images/result_image.png)

Results using vector representation
![](https://github.com/dvalenciar/td3_ddpg_translation_rotation/blob/main/images/result_vector.png)


## Video

A video showing the robot executing the tasks during the training process can be found at:
[https://www.youtube.com/watch?v=ReDdVq_bQuQ](https://www.youtube.com/watch?v=2QBPtrrYIrY)

## Citation
If you use either the code or data in your paper, please kindly star this repo and cite our paper

Cite this paper as: 
Coming soon


## Contact
Please feel free to contact us or open an issue if you have questions or need additional explanations.

