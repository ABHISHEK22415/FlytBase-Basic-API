# Assignment
Build a demo app (using C++/Python FlytAPIs) to make the drone takeoff at 5m, 
move in a square trajectory of side length 6.5m at height 5m and land once the entire mission is over. 
Demonstrate the app and fly the drone in the FlytSIM simulator using python API's.

This code uses PYTHON API's
Following API's are used:
1.Takeoff and landing
2.Position set point from navigation API  to initaite the particular waypoints in its system
3.And at the shutdown API
While executing code in command prompt user need to input the length for the square
Height of takeoff is predefined in the code as 5m (it should be grater than 1.5)
Then save the python code file to a desired location to use in openshell command.

Steps for meeting software requirement:
1.Installing Linux
2.Installing flytsim and flytdocker system  by selecting nvidiasettings.


stepwise commands to be run in the command prompt
1.sudo ./start.sh
2.sudo ./openshell.sh
3.Entering the python file location and the side of square.
4. sudo ./stop.sh
