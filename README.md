# jOSHbox
jOSHbox:  The Open Source Hardware J-box 

Introduction:

   This repository is going to contain all the information gathered pertaining to the feasibility of creating an open source      Vehicle Communication Interface (VCI).   Right now, the project is in a Definition or Conception stage.  I  also imagine        this project will take a long time to complete....
   
   
This project is being created due to an increasing need in the automotive repair industry to provide a means for vehicle firmware replacement and also to utilize manufacturer specific diagnostic strategy and software applications.  The proposed VCI (jOSHbox) will offer multiple diagnostic protocols across a standardized API (J2534-1, ISO 22900-2, etc).


In its current state, the proposed project the project is going to use the following hardware:

beagleboard.org     BeagleBone Black(BBB)

macchina.cc  Under The Dash(UTD) interface board

obd2cables.com   P/N: 144201   Cable, J1962M to J1962F, OBD II Extension Cable, 5ft


It is unsure if this project will grow to support exotic and fast protocols (flexray), without the use of an FPGA, but the PRU should be able to support basic protocol modules such as:

GM SWCAN | 
HS-CAN | 
MS-CAN | 
ISO 9141-2 | 
KWP2000 | 
J1850PWM | 
J1850VPW | 



More to follow
