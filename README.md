# deep-learning-challenge

The deep learning model demonstrated an intermediate performance in predicting the target variable. Despite several attempts, the model was not able to go above 75%, finishing at 72.3%. The loss on the test set was set at 0.6372. Despite the fact this result means that the model has some abilities to predict, it is not extremely reliable, and there is room for improvement. 

Within the model, the target variable was the IS_SUCCESSFUL column. This column indicated whether the crowdfunding campaign was a success or not. The features are the other columns included, such as campaign details and financial metrics. 

The columns that needed to be removed were EIN and NAME, as they were not targets or features. 

I had two layers, the first with 128 neurons and the ReLU activation function, and a second layer with 64 neurons, also with the ReLU activation function. I wasn’t able to achieve the target model performance, however. 

If I were to improve the performance, I could adjust the number of neurons in the layers.

Overall, the model had an accuracy of 72.29% on the test data, which means it is only moderate at predicting campaign success. While it is promising in my opinion, it did not achieve optimal results. 
![image](https://github.com/user-attachments/assets/add47925-37f0-4cd8-bd54-b121209178d4)
