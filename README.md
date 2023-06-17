# Machine-Learning Based Cyber Security

SENG 4610 – Applications of Machine Learning to Software Engineering

## Team Members
- Sam Elgert 
- Ben Lea 

This repository contains the code and documentation for the SENG 4610 project on Machine-Learning Based Cyber Security.

## Design Problem
### Problem Definition
The project's main objective is to design an efficient and resource-friendly security-attack detection system based on machine learning. The system should be capable of detecting and classifying different types of cyber security attacks using various network parameters.

### Objective
- Detect cyber security attacks based on network parameters.
- Classify different types of cyber security attacks into 10 classes.
- Achieve high accuracy and precision.

## Solutions
The project explores multiple solutions to the design problem, utilizing various machine learning algorithms. Some of the solutions include:
- Baseline solution
- Decision Tree Classifier
- Random Forest Classifier
- Deep Neural Network (DNN)
- Soft Voting Ensemble (Vote between DNN, Random Forest)
  

The final solution, the Deep Neural Network, achieved the best performance based on the defined evaluation metrics: was resource-friendly while achieving high accuracy and precision.
<img src="Docs\images\dnn.png" alt="DNN" width="100%">

## DataSet 
<img src="Docs\images\piechart.png" alt="Pie Chart" width="100%">

## Hyperparameter Tuning
<img src="Docs\images\hyperparameter_tuning.png" alt="Hyperparameter Tuning" width="100%">


## Results
### Decision Tree Classifier
<img src="Docs\images\decisionTreeResults.png" alt="Decision Tree Results" width="75%">

### Random Forest Classifier
<img src="Docs\images\randomForestResults.png" alt="Random Forest Results" width="75%">

### Deep Neural Network
<img src="Docs\images\dnnResults.png" alt="DNN Results" width="75%">

### Soft Voting Ensemble
<img src="Docs\images\softVotingResults.png" alt="Soft Voting Ensemble Results" width="75%">

## Conclusion and Future Work
The project successfully developed a machine-learning-based cyber security system capable of detecting and classifying various types of cyber attacks. The Deep Neural Network emerged as the best solution, providing accurate results while consuming minimal memory space. Future work may involve further improving the system's accuracy, exploring additional machine learning algorithms, and addressing any limitations discovered during the project.
