# Calibrating-robot-dynamics
I illustrate the use of multiple linear regression for calibrating robot control. In addition to reviewing the concepts in the multiple linear regression demo,I show to use multiple linear regression for time series data -- an important concept in dynamical systems such as robotics.</br>
The robot data for the lab is taken generously from the TU Dortmund's Multiple Link Robot Arms Project. As part of the project, they have created an excellent public dataset: MERIt -- A Multi-Elastic-Link Robot Identification Dataset that can be used for understanding robot dynamics. The data is from a three link robot:</br>
I focus on predicting the current draw into one of the joints as a function of the robot motion. Such models are essential in predicting the overall robot power consumption. Several other models could also be used.</br> 
The results of this experiment are in the notebook robot_calib.ipynb 
