#### Title: OXYGEN TRANSFER RATE APPLICATION

OBJECTIVE: This project aims to develop a Python-based app for simulating the dissolved oxygen (DO) profile in an aeration tank during wastewater treatment. This app iteratively calculates the oxygen transfer rate (OTR) based on user-defined parameters, such as the initial dissolved oxygen concentration, volumetric mass transfer coefficient, and saturation concentration of oxygen. It then plots the DO concentration over time to visualize the effect of these parameters.

METHODOLOGY: This app uses a mathematical approach to model the dissolved oxygen (DO) levels in an aeration tank over time, making use of the following user inouts:

+ Initial dissolved oxygen concentration (DO).
+ Volumetric mass transfer coefficient.
+ Saturation concentration of oxygen.
+ Duration of time (in hours) over which the DO levels will be tracked.

##### Calculation:
The oxygen transfer rate is calculated iteratively using the formula:
	Transfer Rate = kLa (C* − DO)
	
	where 𝑘𝐿𝑎 is the volumetric mass transfer coefficient, and C is the saturation concentration of oxygen. 
	The DO level is updated over each hour to account for both oxygen transfer and consumption rates.

##### Results: The App generates two results:
+ Oxygen Consumption Rate as mg/L per hour.
+ DO Profile Over Time plotted with Matplotlib: A plot of dissolved oxygen levels over the specified time period, shows how DO fluctuates in response to the oxygen transfer and consumption rates.

#### CONCLUSION
This project helps users understand how oxygen transfer dynamics affect wastewater treatment processes, particularly in maintaining dissolved oxygen levels to support biological activity in an aeration tank.

+ The App
![Screenshot](https://drive.google.com/file/d/1LJLMSUH80FJ1b6e6DwsunKcLWc8VWJzB/view?usp=sharing)

+ The Plot
![Second_Screenshot](https://drive.google.com/file/d/1WMmNNR9NVNLP_p-KMTj7aH3zZDm9KLfB/view?usp=sharing)