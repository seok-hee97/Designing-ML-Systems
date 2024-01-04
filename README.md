# Designing-ML-Systems   
### 머신러닝 시스템 설계.   
[Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/ )    

### [Table of contents]
Preface   
Who This Book Is For   
What This Book Is Not   
Navigating This Book    
GitHub Repository and Community   
Conventions Used in This Book   
Using Code Examples   
O’Reilly Online Learning   
How to Contact Us   
Acknowledgments   
1. Overview of Machine Learning Systems  
When to Use Machine Learning   
Machine Learning Use Cases  
Understanding Machine Learning Systems   
Machine Learning in Research Versus in Production   
Machine Learning Systems Versus Traditional Software   
Summary  
2. Introduction to Machine Learning Systems Design   
Business and ML Objectives  
Requirements for ML Systems   
Reliability  
Scalability  
Maintainability  
Adaptability  
Iterative Process  
Framing ML Problems  
Types of ML Tasks  
Objective Functions  
Mind Versus Data  
Summary  
3. Data Engineering Fundamentals  
Data Sources  
Data Formats  
JSON  
Row-Major Versus Column-Major Format  
Text Versus Binary Format  
Data Models  
Relational Model  
NoSQL  
Structured Versus Unstructured Data  
Data Storage Engines and Processing  
Transactional and Analytical Processing  
ETL: Extract, Transform, and Load  
Modes of Dataflow  
Data Passing Through Databases  
Data Passing Through Services  
Data Passing Through Real-Time Transport  
Batch Processing Versus Stream Processing  
Summary  
4. Training Data  
Sampling  
Nonprobability Sampling  
Simple Random Sampling  
Stratified Sampling  
Weighted Sampling  
Reservoir Sampling  
Importance Sampling  
Labeling  
Hand Labels  
Natural Labels  
Handling the Lack of Labels  
Class Imbalance  
Challenges of Class Imbalance  
Handling Class Imbalance  
Data Augmentation  
Simple Label-Preserving Transformations  
Perturbation  
Data Synthesis  
Summary  
5. Feature Engineering  
Learned Features Versus Engineered Features  
Common Feature Engineering Operations  
Handling Missing Values  
Scaling  
Discretization  
Encoding Categorical Features  
Feature Crossing  
Discrete and Continuous Positional Embeddings  
Data Leakage  
Common Causes for Data Leakage  
Detecting Data Leakage  
Engineering Good Features  
Feature Importance  
Feature Generalization  
Summary  
6. Model Development and Offline Evaluation  
Model Development and Training  
Evaluating ML Models  
Ensembles  
Experiment Tracking and Versioning  
Distributed Training  
AutoML  
Model Offline Evaluation  
Baselines  
Evaluation Methods  
Summary  
7. Model Deployment and Prediction Service  
Machine Learning Deployment Myths  
Myth 1: You Only Deploy One or Two ML Models at a Time  
Myth 2: If We Don’t Do Anything, Model Performance Remains the Same  
Myth 3: You Won’t Need to Update Your Models as Much  
Myth 4: Most ML Engineers Don’t Need to Worry About Scale  
Batch Prediction Versus Online Prediction  
From Batch Prediction to Online Prediction  
Unifying Batch Pipeline and Streaming Pipeline  
Model Compression  
Low-Rank Factorization  
Knowledge Distillation  
Pruning  
Quantization  
ML on the Cloud and on the Edge  
Compiling and Optimizing Models for Edge Devices  
ML in Browsers  
Summary  
8. Data Distribution Shifts and Monitoring  
Causes of ML System Failures  
Software System Failures  
ML-Specific Failures  
Data Distribution Shifts  
Types of Data Distribution Shifts  
General Data Distribution Shifts  
Detecting Data Distribution Shifts  
Addressing Data Distribution Shifts  
Monitoring and Observability  
ML-Specific Metrics  
Monitoring Toolbox  
Observability  
Summary  
9. Continual Learning and Test in Production  
Continual Learning  
Stateless Retraining Versus Stateful Training  
Why Continual Learning?  
Continual Learning Challenges  
Four Stages of Continual Learning  
How Often to Update Your Models  
Test in Production  
Shadow Deployment  
A/B Testing  
Canary Release  
Interleaving Experiments  
Bandits  
Summary  
10. Infrastructure and Tooling for MLOps  
Storage and Compute  
Public Cloud Versus Private Data Centers  
Development Environment  
Dev Environment Setup  
Standardizing Dev Environments  
From Dev to Prod: Containers  
Resource Management   
Cron, Schedulers, and Orchestrators  
Data Science Workflow Management  
ML Platform  
Model Deployment  
Model Store  
Feature Store  
Build Versus Buy  
Summary  
11. The Human Side of Machine Learning  
User Experience  
Ensuring User Experience Consistency  
Combatting “Mostly Correct” Predictions  
Smooth Failing  
Team Structure  
Cross-functional Teams Collaboration  
End-to-End Data Scientists  
Responsible AI  
Irresponsible AI: Case Studies  
A Framework for Responsible AI  
Summary  
Epilogue  
Index  
About the Author  


### [reference]


- 머신러닝 시스템 설계 도서

- https://velog.io/@heyggun/