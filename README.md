## HOPE-4-CANCER

### 1. Business Problem
#### 1.1. Description
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/

Data: Memorial Sloan Kettering Cancer Center (MSKCC)

Download training_variants.zip and training_text.zip from Kaggle.

Context:
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198462

### Problem statement :
Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

### 1.2. Source/Useful Links
Some articles and reference blogs about the problem statement

https://www.forbes.com/sites/matthewherper/2017/06/03/a-new-cancer-drug-helped-almost-everyone-who-took-it-almost-heres-what-it-teaches-us/#2a44ee2f6b25
https://www.youtube.com/watch?v=UwbuW7oK8rk
https://www.youtube.com/watch?v=qxXRKVompI8

###1.3. Real-world/Business objectives and constraints.
No low-latency requirement.
Interpretability is important.
Errors can be very costly.
Probability of a data-point belonging to each class is needed.

<h2>2.2. Mapping the real-world problem to an ML problem</h2>
<h3>2.2.1. Type of Machine Learning Problem</h3>
<h3>2.2.2. Performance Metric</h3>

Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment#evaluation

### Metric(s): 
* Multi class log-loss 
* Confusion matrix 

<h3>2.2.3. Machine Learing Objectives and Constraints</h3>
<p> Objective: Predict the probability of each data-point belonging to each of the nine classes.
</p>
<p> Constraints:
</p>

* Interpretability
* Class probabilities are needed.
* Penalize the errors in class probabilites => Metric is Log-loss.
* No Latency constraints.
