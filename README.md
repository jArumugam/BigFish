Hello!


<img src="https://github.com/jArumugam/BigFish/blob/master/results/unweighted_graph_Y16_full.png" width="300" height="300" /><img src="https://github.com/jArumugam/BigFish/blob/master/results/weighted_graph_Y16_partial.png" width="300" height="300" />

### Context
I found many interesting projects that study NYC Taxi Data such as [Ride Demand Prediction1](https://github.com/Sapphirine/Analyzing1Billion-NYC_Yellow_Taxi_Rides_for_Ride_Demands_Prediction) and [Ride Demand Prediction2](http://sdaulton.github.io/TaxiPrediction/).
Most of them predict taxi-ride demands based on features like time, location and weather. 

### Objective
I want to add a new dimension. 

### Scope
I intend to use network analysis tools to study the data. 

### Motivation
There is an immediate advantage in using network analysis tools. 
Previous studies predict pickup amount, trip fare, etc., in real-time. 
However, this information as such would need further processing for making decisions. 
Network analysis offers rich models to answer many actionable questions. 
Further, network abstraction allows the solution to be useful in a wide range of other applications

### Actionable questions
The question(s) I address are the following:
1. **_Given taxi-ride demand predictions, can we suggest optimal pick-up locations for a taxi driver?_** 
  - I want to consider a dynamic situation where the suggestion machine accounts for competition (or supply) from other taxi drivers. 

2. **_Are there good pickup-drop cycles?_** 
  - This is optimizing over longer periods of time instead of looking at a particular instance 

### Plan
1. Abstract data using networks 
2. Formulate appropriate optimization problems 
3. Visualize results
4. Get taxi-demand prediction working 
5. Refine questions. Significant improvements to steps 1, 2, 3, and 4 
6. Scale up 
7. Real-time app using cloud services 

### Timeline
- March 05 2017 to March 15 2017: Project definition 
- March 16 2017 to March 20 2017: [Feasibility check](https://github.com/jArumugam/BigFish/blob/master/notebooks/NB01%20Data%20Exploration.ipynb) 
- March 20 2017 to March 30 2017: Version 0.1 
- April 01 2017 to April 15 2017: Taxi-demand prediction, step 6 feasibility 
- April 15 2017 to April 30 2017: Integrate steps 1, 2, 3, and 4 
- May 15 2017 to May 30 2017: Step 5 first iteration 
- June 01 2017 to June 10 2017: Network and collaborate 
- June 11 2017 to June 20 2017: Scale up and step 7 
- June 21 2017 to June 30 2017: Step 5 second iteration 
- July 01 2017 to July 15 2017: Communicate 
- July 16 2017 to July 30 2017: Explore other applications 

### You are welcome!
Interested data scientists who are willing to share specific resposibilities are welcome to participate. 

### Thank you for your time! 
