# Calculate-Accuracy-and-Decision-Tree
Calculate Accuracy 



-The dataset used contains characteristics of wine quality

-I only used type,fixed acidity and volatile acidity groups to make precision calculation easy because there are so many data groups

-Since there are 6497 rows in total, I made this calculation on the first 100 data.

-No matter how large the test size is, you will usually reach a hundred percent result because the size of the data we use is small and there are not many data groups.

-if you want to try yourself You can write a larger number instead of :100 in the data=df[["fixed acidity","volatile acidity","type"]][:100] line of code.

************************************************************************************************************************************************************************

Decision Tree

-Decision tree is an algorithm used in machine learning.

-The decision tree of the data I used shows the probabilities of the wine being red or white.

-Here I made a decision tree that directly covers all the data, but you can change it again to make it simpler.

-You can use joblib and tree libraries.
If you are looking at old videos or resources, you may get an error because of the library you called due to the update in jupyter.

-Codes you need to use in the new update:import joblib,from sklearn import tree


![wine-quality (1) dot](https://user-images.githubusercontent.com/73754203/222736506-2bcf154a-f253-4d2b-9ba7-426bf04013a1.svg)


You can follow me on Github and Kaggle;

Kaggle:https://www.kaggle.com/keremkarayaz

Github:https://github.com/kerem480

