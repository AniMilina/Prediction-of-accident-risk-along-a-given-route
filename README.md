# Prediction-of-accident-risk-along-a-given-route  

It is necessary to create a system that could assess the risk of an accident along the chosen route  
Risk means the likelihood of an accident with any damage to the vehicle.  

Once the driver has booked a car, got behind the wheel and chosen a route, the system must assess the level of risk. If the risk level is high, the driver will see a warning and route recommendations  

The idea of creating such a system is at the stage of preliminary discussion and development. There is no clear operating algorithm or similar solutions on the market yet.  

The current task is to understand whether it is possible to predict road accidents based on historical data from one of the regions  

Idea for solving a problem from a customer:  

Create an accident prediction model (target value - at_fault (culprit) in the parties table) • For the model, select the type of culprit - only car (car)  
• Select cases where the accident resulted in any damage to the vehicle other than the SCRATCH type (scratch)  
• For modeling, limit yourself to data for 2012 - they are the most recent  
• A prerequisite is to take into account the age of the car  

Based on the model, explore the main factors of road accidents  
Understand whether the modeling results and analysis of the importance of factors will help answer the questions:  
• Is it possible to create an adequate system for assessing driving risk when issuing a car?  
• What other factors need to be considered?  
• Does the car need to be equipped with any sensors or a camera?  

The customer invites you to work with the incident database and formulate your own ideas for creating such a system  

Our task:  

Load data from a remote database;  
Conduct primary data research;  
Perform an analysis of accident factors;  
Prepare data for models;  
Build several different models;  
Choose the best model;  
Analyze the selected model;  
Analyze the main factors influencing the likelihood of an accident;  
Draw a conclusion: to what extent is it possible to create an adequate risk assessment system when issuing a car;  
Suggest: what factors need to be collected to improve the model.  
