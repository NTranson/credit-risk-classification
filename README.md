# Credit Risk Classification Challenge

## Overview of Analysis
In this ananlysis, I created a machine learning model that utilized supervised learning to indentify and analyze loan data. By taking into account several factors such as: loan size, interest, total debt, etc, the model identified trends and was able to determine if a loan was high risk or low risk (healthy). 

## Results: Logistic Regression Machine Learning Model:
* Overall Accuracy of model: 99%
* Precision for identiifying healthy loans (0): Classification report rounded to 100%. However, because there were some false negatives seen in the confusion matrix, it is more accurate to state that the precision was greater than 99.5%.
* Recall for healthy loans: 99%
* Precision for high-risk loans: lower than healthy loan precision at 85%
* Recall for high-risk loans: also lower than healthy loan recall at 91%

## Summary 
The model performed very well overall, accurately predicting both healthy and high-risk loans. While it was more effective for healthy loans, its precision and recall rates were considered strong for both outcomes. For a lending services company, avoiding approving high-risk loans is crucial. This model's higher recall than precision for high-risk loans suggests it's better at avoiding false negatives, which is more beneficial in avoiding risky borrowers. Despite potentially declining some borrowers who would have been healthy, it's preferable to approving more loans at risk of default. The model's 91% recall for high-risk loans is robust, making it a recommended choice for the company, likely outperforming their current model. A pilot period could be used to compare the models before full implementation if there are concerns about the small error rate.
