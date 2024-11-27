# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
![1](https://github.com/user-attachments/assets/1902711d-e1b4-42ea-8331-33d08544bf54)
![2](https://github.com/user-attachments/assets/e9360953-364f-4dc4-a658-a14281774028)
![3](https://github.com/user-attachments/assets/4b3a149d-9776-4648-8823-e42507b3297e)
![4](https://github.com/user-attachments/assets/7be12945-9de7-4b0c-8f57-960642631c39)
![5](https://github.com/user-attachments/assets/e1f7bac7-67c9-4575-a728-8a00723627c4)
![6](https://github.com/user-attachments/assets/e58e95a1-60b7-41cb-a6a5-cdcaf4cf2e5d)
![7](https://github.com/user-attachments/assets/58e790e1-01f3-461a-9976-a466128fcceb)
![8](https://github.com/user-attachments/assets/8668b974-fbf5-4a99-8b2b-cf438287e62a)
![9](https://github.com/user-attachments/assets/fd6ed1f5-67cc-41e4-97e3-411b06958f6a)
![10](https://github.com/user-attachments/assets/a0339468-10db-40df-af7d-95714a3dc183)
![11](https://github.com/user-attachments/assets/25acac07-22ee-4db7-baa8-359fe1886ec9)
![12](https://github.com/user-attachments/assets/7af54729-cab5-41d2-975a-57a7b176aac2)
![13](https://github.com/user-attachments/assets/cca3305e-7a10-49ec-a7d6-7e67a8d74622)
![14](https://github.com/user-attachments/assets/7c2f43a1-b929-43c8-a147-ec302f48a209)

# RESULT:
 The given data was read, Feature Scaling and Feature Selection processes were performed, and the data was saved to a file.
