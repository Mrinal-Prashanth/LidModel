# LidModel
Created a working lid model for a rocket launcher. Used tiva c series as well as a MSP controller setup in a master-slave network in order to communicate and control the servo motor that controls the lid. Made a model file using cad software and got it 3d printed.

The model can be scaled up to a larger sized model (also attached) provided a more powerful servo motor. In this case the available servo motor was only powerful enough to control a lid that is around 1.5 times smaller than our initial model.

MSP430 is the slave and is also connected to the servo motor. It communicates with the master (Tiva C) and rotates the servo motor through an angle that is sufficient for the rocket to launch. 

The pins and connections are mentioned in the c code but may need to be updated. 
