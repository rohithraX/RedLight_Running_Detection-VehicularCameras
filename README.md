# RedLight_Running_Detection-VehicularCameras 
The aim of this project is to detect Red Light advancement in Traffic automatically using vehicular cameras.
It is based on Image Processing and is written in Matlab(R2017b). The basic idea of this project and its working are given in text file with name 'Procedure'.

User needs to install Matlab with Image acquisition Toolbox and Image Processing Toolbox. Might work for older versions without any major errors.

Note that the aim of the project is to detect if a vehicle skips a red light and moves forward with a camera installed in the vehicle facing forward. Try to think of a logic or an algorithm for each step before going through code or searching for pre-defined libraries.This code is very simple form of the project and can be extended to a more complex form involving more processes,thus increasing accuracy.

Also not that the  variable n value in main1.m file depends on your frames count and I took 6 frames to demonstrate the working of this model. The dataset is created by placing circles on frames that act as red traffic lights for demonstration. As the red light disappears at 6th frame log is entered into logbook. 
