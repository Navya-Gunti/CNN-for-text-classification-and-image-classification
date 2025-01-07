Compare the performance of CNN for text classification and image classification. 
 
The text sentimental analysis is performed for movie review dataset of 50000.  The data was divided into two parts, negative and positive and labelled as 0 and 1. By using the layers as below we achieved the accuracy as 88%.

 
<img width="468" alt="image" src="https://github.com/user-attachments/assets/e3e8010d-e62a-4b19-9f56-05e587bf54d7" />


For image classification, we consider the 5- celebrity dataset. pre-trained Keras FaceNet model. To fit the model, we considered the SVC model. And the accuracy we achieved is the 100%.

While comparing the performance of both the task, we observe that image classification much more better than text classification, since it achieved more performance accuracy than the other. An advantage of utilizing an image classifier is that the weights trained on image classification datasets can be used for the encoder. This can be considered a benefit as the image classification datasets are typically larger, such that the weights learned using these datasets are likely to be more accurate.
![image](https://github.com/user-attachments/assets/896e4340-0965-4273-ad1b-903a8e11a078)
