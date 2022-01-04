# Pet_pawpularity overview
It's a beginner friendly code for finding the popularity of pets using supervised machine learning for kaggle's competition.
This code recieved bronze award in just 5 days after uploading it. 
If you're a professional the please feel free to help me improve this code as no code is perfect.
# Tools and Techniques used
I've used transfer learning on Inception_v3 for training the model to find the features of the pets from the given pictures. After training the model i've used validation data to predict the features and then normalizing it between 1 to 0. Then the normalized features are passed through XGBoost model for training it to find the popularity percentage of pets. 
