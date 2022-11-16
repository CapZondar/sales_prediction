# Food Sales Prediction
---
## Simple Machine Learning regression model using SK Learn

#### We are tasked to build a machine learning model to predict the sales for each item.
#### All data cleaning and manipulation steps are documented in the Jupyter notebook itself.
---
### 2 glaring observations were found when exploring the data

* Fruits and vegetables is the top selling products for all of the outlets recorded
* Despite this fact, the most expensive item that the outlets are seeling are household items which is only the 3rd item that has most sales.
![image](https://user-images.githubusercontent.com/110689453/202088358-6041a1c9-e456-42f9-ba4c-633080157882.png)

* Having a  bigger store doesn't necessarily mean more sales. On the graph below, it can be observed that Medium sized store have more sales than the high outelet size.
![image](https://user-images.githubusercontent.com/110689453/202088606-b1643dbb-9ecc-4c22-a1e5-67d0cbd49327.png)
---
# Testing 2 different models.
* On this task, we have tried 2 different regression models. A simple Linear Regression and a Regression Tree.
* Based on the testing results, we have achieved a higher accuracy for Regression Tree with an R2 score of .58 or 58% as compared to .57 to Linear Regression.
* Due to higher R2 score, we will be implementing the Regression Tree model on this dataset. 
(The whole process can be inspected on the notebook itself)
