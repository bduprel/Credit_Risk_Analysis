# Credit_Risk_Analysis


##Overview 
The project was completed to evaluate the credit worthiness of different credit applicants. Data was resampled to create a model via the RandomOverSample and SMOTE algorithms. Then a logistic regression was used to actually create predictions based on the model. 

##Results
Smoteenn
![image](https://user-images.githubusercontent.com/106126621/194207422-55c6d067-1ab7-4bc0-a33a-43fc2462b830.png)
![accuracy1](https://user-images.githubusercontent.com/106126621/194206293-1e0bd138-2c6c-41ab-bb75-00e097108f7a.png)
Smote
![image](https://user-images.githubusercontent.com/106126621/194207459-93b18de7-42c6-47ef-a7f6-d16fc9625333.png)
![accuracy2](https://user-images.githubusercontent.com/106126621/194206295-f39a4c23-4bda-43f4-916f-9fc5cdd1d88d.png)
RandomOverSampling
![image](https://user-images.githubusercontent.com/106126621/194207493-708b5ba7-2bf2-4d8d-987b-3bf13cee4969.png)
![accuracy3](https://user-images.githubusercontent.com/106126621/194206296-c4f47117-6c13-46e6-a950-ae56b609dd76.png)
ClusterCentroids
![image](https://user-images.githubusercontent.com/106126621/194207563-0d42ecad-856a-4518-a975-e5b0c9569436.png)
![accuracy4](https://user-images.githubusercontent.com/106126621/194206297-14930c33-96d9-4c5c-a72a-8fb953bbbce5.png)
EasyEnsembleClassifier
![image](https://user-images.githubusercontent.com/106126621/194207608-07ff2883-307d-44f5-b757-523509a146e8.png)
![accuracy5](https://user-images.githubusercontent.com/106126621/194206298-f3c7b181-562d-49d6-a4af-f8dd6006134e.png)\
BalancedRandomForrest
![image](https://user-images.githubusercontent.com/106126621/194207645-8726f776-3851-4575-9a12-590eccdef412.png)
![accuracy6](https://user-images.githubusercontent.com/106126621/194206300-fb240def-a38b-4747-89bb-75d4dc69827d.png)

Above are the accuracy scores, confusion matricies, and classifcation reports of the different models. None of the models are very strong seeing as the accuracy scores rang from 48 to 65% (a stronger model is 70 to 90% accuracy score). But each model shares a percision score of 0.01



##Summary
Based on the images above, ClusterCentroids is the strongest with an accuracy score of 65.6%. However, this does not seem like a very strong model with such a low accuracy score. This model is the best of the choices above, but I would not recommend using it. 
