<h1 align="center">
  <br>
Continuous Action Deep Reinforcement Learning for Dexterous Robotic Manipulation
  <br>
 </h1>
 
  <p align="center">
    • Centre for Automation and Robotic Engineering Science •
  </p>

  <p align="center">
    • New Dexterity Research Group •
  </p>
  
  <p align="center">
    University of Auckland
  </p>
  
  
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

## Network Architecture 
Two state-space representations were used as state input for both DDPG and TD3. The below images describe the architecture used for the critic and actor NN (for more details, please see the paper)

 ![](https://github.com/dvalenciar/td3_ddpg_translation_rotation/blob/main/images/actor.png)




## Results
For testing purposes, this robot is trained to complete two manipulation tasks, translation and rotation of an object. DDPG and TD3 were implemented

 ![](https://github.com/dvalenciar/td3_ddpg_translation_rotation/blob/main/images/Results_vector.png)

## Video
A video showing the robot executing the tasks during the training process can be found at:
https://www.youtube.com/watch?v=ReDdVq_bQuQ

## Citation
If you use either the code or data in your paper, please kindly star this repo and cite our paper

Cite this paper as: 
Coming soon


## Contact
Please feel free to contact us or open an issue if you have questions or need additional explanations.

## References
- ME Thesis – Alex Hayashi  https://newdexterity.org/manipulationtestbed/
- DDPG https://arxiv.org/abs/1509.02971 
- TD3  https://arxiv.org/pdf/1802.09477.pdf
