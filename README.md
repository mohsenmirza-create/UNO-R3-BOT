PROJECT OVERVIEW:
Code base for ELEGOO R3 UNO robot (by Mohsen Mirza and Mohib Awan), coded with C++ in Arduino IDE.

STRUCTURE:
-Past Projects (individual mini projects built during given lecture time)
-Functions (individual sects of code with delibrate functiontionality, packaged for easy reuse)
-Project Development (main project folder where projects are developed, a basic essentials file by Eric Rapos (contains motor pins, servo and gyro functions, etc...) is available, as well as a project file containing a basic project structure for easy development. 

HARDWARE: 
The R3 comes with a set of motors (for wheels), servos, and two sensors (gyro and ultrasonic).

-Wheels have a tendancy to shift from place after repated use, causing the movement of the robot to become slanted. Long term fix is to tighten the screws of the motors. Quick method would be to manually move the wheels by hand into the correct position. Re

-ultrasonic sensor has issues with consistently reading the correct light levels. For example the sensor is placed on an area that has a light level of 50, it will momentarily output 300 even though the reading should be 50. A fix for this is creating a special case where the robot discards the outlier reading so it behaves as expected.

INSTRUCTIONS:
-Open a terminal (Git Bash, PowerShell) and type "git clone https://github.com/mohsenmirza-create/UNO-R3-BOT.git" 

