UAS Falling Motion Calculator
This Python script calculates the final x-position of a Unmanned Aircraft System (UAS) falling from a specified initial height, accounting for the effects of air drag in both the x and z axes. The calculation integrates the motion due to the initial velocity of the UAS (v0) with the motion caused by wind, providing a comprehensive understanding of the UAS's expected trajectory after a Loss of Control (LOC) event.


git clone https://github.com/ptlockey/UAS_Trajectory.git


Input Parameters:

initial_height: Initial height from which the UAS falls (in meters).
m: Mass of the UAS (in kilograms).
u: Wind speed (in meters per second).
surface_pressure_mb: Surface pressure (in millibars).
surface_temp_celsius: Surface temperature (in degrees Celsius).
Cd: Drag coefficient of the UAS.
A: Cross-sectional area of the UAS (in square meters).
v0: Initial velocity of the UAS (in meters per second).
Output:

Initial temperature and air density at the specified initial height.
Final x-position of the UAS.
X-position due to initial velocity only.
Final x-position due to wind force alone.
Final velocity components (x, z, and total).
Total time until the UAS reaches the ground.

The script uses the Euler numercial integration method.
​
 
Notes
Ensure all input parameters are provided in the correct units for accurate results.
The script provides detailed output regarding the UAS's motion, allowing users to understand the impact of wind and initial velocity on its trajectory.
Feel free to explore the code, modify input parameters, and utilize the output for further analysis. For any issues or enhancements, please raise them in the repository's issue tracker. Happy coding!

Repository Link: https://github.com/ptlockey/UAS_Trajectory.git
