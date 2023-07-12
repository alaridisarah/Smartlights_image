# **Model deciding on smart lights.**

We are all familiar with smart light in smart homes and how important it is for human comfort and waste energy use reduction. It is also possible to perform a similar system to manage the light all time without human interference unlike other several applications that require a command of the human voice or through clicking off or on in smartphone applications.


This model is proposed to help in deciding for open light or close or limited lights based on time, it works by taking a picture from a security camera during certain hours and then classifying this image to decide the state of lights.
## **Dataset**

The [Time of Day dataset](https://www.kaggle.com/datasets/aymenkhouja/timeofdaydataset) is a collection of images representing different times of the day, sunrises/sunsets, and daytime and nighttime scenes. All images have been rescaled to 224 x 224 x 3 pixels. The images were scraped from the online photography community, Unsplash, and depict various locations and weather conditions, such as clear skies, cloudy days, etc.

The dataset was collected to be used for computer vision models that can recognize and classify images based on the time of day. The built model will identify the time of day and lighting conditions in an image, which can be helpful in a variety of applications. The dataset contains 2671 high-quality images, carefully curated and labeled to ensure accuracy and consistency.



![datasetimage](https://k.top4top.io/p_2708pqh681.png)

## **Models**
In this project there are two models, the first model(Feature Extraction + ML model) and the second is a deep learning model.

The first model built in this project will pass into three steps:
1. Preprocessing
2. Feature extraction(HOG)
3. Machine learning classifier

while the DL model was pre-trained [Effeicent netv2](https://www.kaggle.com/code/kkhandekar/timeofday-classification-efficientnet-v2-b0-98)

## Done by:
- [Sarah Alaridi](https://github.com/alaridisarah)
- [Sadeem Alqahtani]()
- [Sarah Alsarami](https://github.com/SarahAlsarami)
- [Asia Alrajehi](https://github.com/Asiaalrajeh)

