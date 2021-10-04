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

## Reinforcement Learning with AWS DeepRacer
### Reinforcement Learning Concepts
Basic reinforcement learning terms in the context of AWS DeepRacer.
![dl](https://user-images.githubusercontent.com/45710599/135882243-f360949d-00f2-4552-aa9f-a2a5bdae190a.png)
- **Agent :** The agent is the AWS DeepRacer car and its goal is to finish * laps around the track as fast as it can while, in some cases, avoiding obstacles. 
- **Environment :** For AWS DeepRacer, this is a track in our simulator or in real life.
- **State :** Each state is an image captured by its camera.
The car’s initial state is the starting line of the track and its terminal state is when the car finishes a lap, bumps into an obstacle, or drives off the track.
- **Action :** An AWS DeepRacer car approaching a turn can choose to accelerate or brake and turn left, right, or go straight.
- **Reward :** A reward function is an incentive plan that assigns scores as rewards to different zones on the track. 
- **Episode :** An episode begins at the initial state, when the car leaves the starting position, and ends at the terminal state, when it finishes a lap, bumps into an obstacle, or drives off the track. 

In a reinforcement learning model, an **agent** learns in an interactive real-time **environment** by trial and error using feedback from its own **actions**. Feedback is given in the form of **rewards**.
## Generative AI with AWS DeepComposer
### AWS DeepComposer
AWS DeepComposer gives you a creative and easy way to get started with machine learning (ML), specifically generative AI. It consists of a **USB keyboard** that connects to your computer to input melody and the **AWS DeepComposer console**, which includes AWS DeepComposer Music studio to generate music, **learning capsules** to dive deep into generative AI models, and **AWS DeepComposer Chartbusters challenges** to showcase your ML skills.
