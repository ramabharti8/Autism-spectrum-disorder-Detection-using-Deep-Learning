# Autism-spectrum-disorder-Detection-using-Deep-Learning

## Overview

Autism Spectrum Disorder (ASD) is a complex neurodevelopmental disorder that affects social interaction, communication, and behavior. Early diagnosis and intervention are crucial for improving outcomes for individuals with ASD. Traditional diagnostic tools often rely on subjective assessments, which can be time-consuming and expensive. This project explores the potential of machine learning, specifically deep learning techniques, to enhance the accuracy and efficiency of ASD diagnosis.

## Dataset

We used a combination of three datasets: "Autism-Child-Data.txt," "Autism-Adolescent-Data.txt," and "Autism-Adult-Data.txt." These datasets include information on 1,100 individuals from different age groups and countries. They encompass demographic information, behavioral features, and clinical diagnoses of ASD.

## Methodology

Our approach involved the application of convolutional and recurrent neural networks to extract features from the input data and predict ASD diagnosis. The deep learning model was trained on 80% of the dataset and validated on the remaining 20%. The training was conducted using Python with the Keras framework and TensorFlow as the backend.

## Feature Set

The features used in the model include demographic information such as age, sex, and ethnicity, as well as behavioral features like communication, social interaction, and repetitive behaviors. These features were pre-processed and normalized before being fed into the deep learning model.

## Results

The deep learning model demonstrated exceptional performance, achieving an accuracy of 95% on the test set. It outperformed traditional machine learning methods like logistic regression and support vector machines. Precision, recall, and F1-score metrics were also evaluated, highlighting the model's proficiency in detecting both ASD and non-ASD cases.

## Feature Importance

An analysis of the most important features used by the model revealed that communication and social interaction were the most influential factors in predicting ASD diagnosis. These findings align with the known areas affected by ASD, underscoring the potential of deep learning techniques for identifying predictive features.

## Implications

The findings of this study hold significant implications for early diagnosis and intervention for individuals with ASD. Leveraging machine learning techniques can potentially enhance the accuracy and efficiency of ASD diagnosis, facilitating earlier intervention and better outcomes. However, it's essential to acknowledge that this study has limitations, primarily due to the dataset's size and scope. Further research is warranted to validate the model on larger and more diverse datasets and to explore the potential of incorporating additional data types, such as neuroimaging or genetic data.

## Conclusion

In conclusion, this study illustrates the promise of deep learning techniques for predicting ASD diagnosis based on behavioral and demographic data. The results suggest that machine learning can play a vital role in enhancing the accuracy and efficiency of ASD diagnosis, ultimately improving outcomes for individuals with ASD. Future research should focus on expanding the dataset and exploring the integration of other data types to enhance the model's performance and generalizability.
