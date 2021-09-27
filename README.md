# AWS Machine Learning Foundations Scholarship 
##  AWS ML services
With AWS, you can build, train, and deploy your models fast. **Amazon SageMaker** is a fully managed service that removes complexity from ML workflows so every developer and data scientist can deploy machine learning for a wide range of use cases.
## ML infrastructure and frameworks
AWS Workflow services make it easier for you to manage and scale your underlying ML infrastructure.
![ml](https://user-images.githubusercontent.com/45710599/134913567-96edc821-d422-4319-9eac-aac194631045.png)
## Computer Vision with AWS DeepLens
### AWS DeepLens
AWS DeepLens allows you to create and deploy end-to-end computer vision–based applications. 
### How AWS DeepLens works
AWS DeepLens is integrated with multiple AWS services. You use these services to create, train, and launch your AWS DeepLens project. You can think of an AWS DeepLens project as being divided into two different streams as the image shown.

<img width="495" alt="dp" src="https://user-images.githubusercontent.com/45710599/134917289-1671c91d-01f6-4fda-98dd-5d68caf8224e.png">

* First, you use the AWS console to create your project, store your data, and train your model.
* Then, you use your trained model on the AWS DeepLens device. On the device, the video stream from the camera is processed, inference is performed, and the output from inference is passed into two output streams:      
   - Device stream – The video stream passed through without processing.
   - Project stream – The results of the model's processing of the video frames.
