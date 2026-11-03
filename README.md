# Credit Card Fraud Detection 

![Fraud Detection](https://img.shields.io/badge/Fruad_Detection-009688?flat&logoColor=white)
![RandomForestClassifier](https://img.shields.io/badge/Random%20Forest%20Classifier-2196F3?style=flat)

## About the Project:
I used ```RandomForestClassifier``` to classify the given transactions as legit or fraud, using a data on which PCA had been performed to keep privacy of insights.
The model responded with a decent performance as shown below:

<img width="473" height="94" alt="image" src="https://github.com/user-attachments/assets/5e9fa9ce-00a3-4d14-b396-d48dfbbf972a" />

Where 1 showing the Fraud cases and 0 showing the legit cases. **Precision** tells us out of all the fraud cases the model classifies, 
92% of them were actual fraud cases and **Recall** tell us out of all the Fraud cases, our model was able to find 70% of them.

## Libraries Used:
+ ```sci-kit```
+ ```pandas```
+ ```matplotlib```
+ ```numpy```

## Further Contributions:
I'm planning on using ```XGBClassifier``` To improve my recall and precision.
