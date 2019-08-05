# Sign Language Classification in real-time

## Description

Using transfer learning on a MobileNetV2 developed a model to classify the American Sign Language in real-time.
The model was built on tensorflow (Keras) and the cv2 library for the video feed and region of interest extraction.
Image augmentation was also used to prevent overfitting of the training set.
The training data was obtained from the ASL Dataset on Kaggle.

Below is a short demo of the model's performance after only 40 epochs

![](signlanguage.gif)
