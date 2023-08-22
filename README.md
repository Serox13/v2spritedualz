#SEROX13 - Ender 3v2 CR TOUCH/DUAL Z/Sprite Extruder/ 4.2.2 board/linear x-axis
################### SETTINGS TO CHANGE #########################################
serial i.d/webcam with timelapse/input shaping with accelerometer/pressure advance/extruder rotation distance/klipperScreen over wifi can be done over USB/Crowsnest/adaptive meshing and purge
but all the basic settings are there
Config files for klipper installs
This is working bin config files for Ender 3 V2 Sprite extruder and dual z-axis/ 4.2.2 board
i have done a lot of testing to get these numbers [glass plate with creality clips]
These are all working files from 2023
i went through hours of pain getting Klipper installed and calibrated to where it is now
i hope i can help some ppl save a few hrs in the process of installing Klipper
######
Please understand i have seen lots of different numbers ranging from 7.5-33 for rotation distance for the extruder all i can say is use my numbers and test test test this will 50% of problems from under or over-extruding/
if you hear the nozzle rubbing on prints but not on other prints then check the extrusion and flow rates even a number 
is far as 1 [should be 26 but is at 27] can cause you headaches. calibrate the extruder steps with this page >>> https://www.service-uplink.de/esteps_cal/calculator.php to calculate your rotation distance do it 3 times and calculate the average and do a test print
pressure advance make sure you do your own testing and make sure you calculate the values correctly x 0.005 is the factor you want to times for direct drive
a lot of problems were from a faulty styepper motor on the z axis and the brass couplers rolerances were horrible, i swapped the motor out and put new POM couplers
