# Facial-Emotion-Detection
This is Emotion Detection using CNN.


STEP 1:
========
Convert the CSV files into a folder of actual images of size 48*48.
Code reference : convert_CSV_to_Images.ipynb

STEP 2:
========
The number of images for "Disgust" classes is less, hence augmented it . 
Disgust.zip has the images

STEP 3:
========
Construct a CNN to classify the images into 7 emotions : Anger, Fear, Disgust , Neutral, Happy, Sad , Surprise.
I used a train set of 90% and test set of 10% manually calculating the number of images.
Acquired around 70% of accuracy . 
Code Reference: Emotion Detection.ipynb

STEP 4:
=======
Use the built model for inference on a real time emotion detection.
Uploaded Model.zip with the model architecture alog with its weights.
Code Reference : EmotionDetection_testApp.ipynb

Dataset : FER2013 ( https://www.kaggle.com/deadskull7/fer2013 )

References : Blogs from Medium, towardsDatascience and MachineLearningMastery
