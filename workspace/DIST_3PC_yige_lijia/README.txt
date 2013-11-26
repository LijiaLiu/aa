Project HW1

Slip days used (this project): ___2___ Slip days used (total): ___2___

Group members:
Yige Hu - yh6596
Lijia Liu - ll27879


In the folder of DIST_3PC, the "dist_3pc.jar" is the final version of our program, while "dist_3pc_debug.jar" is the debug version. In the debug version, the program will halt and wait for the user's input for several times, thus producing chance for killing them, or time-out. Files named like "config0, config1..." are the configuration files.

You could run them like this:

java -jar dist_3pc.jar config0
java -jar dist_3pc.jar config1
java -jar dist_3pc.jar config2

or

java -jar dist_3pc_debug.jar config0
java -jar dist_3pc_debug.jar config1
java -jar dist_3pc_debug.jar config2





EXTRA POINT:

1. The precommit should also be logged into DT Log.
2. If the coordinator sends precommit and then broke, according to the textbook, the recovery determination should be abort, but the correct one is commit.


