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

### AWS DeepComposer music studio
To generate, create, and edit compositions with AWS DeepComposer, you use the AWS DeepComposer Music studio. To get started, you need an input track and a trained model.

For the input track, you can use a sample track, record a custom track, or import a track.
<img width="1143" alt="et" src="https://user-images.githubusercontent.com/45710599/135896222-ccb58583-7c46-41fc-94d7-686bb8e4d7c8.png">

Each AWS DeepComposer Music studio experience supports three different generative AI techniques: generative adversarial networks (GANs), autoregressive convolutional neural network (AR-CNNs), and transformers.
- Use the GAN technique to create accompaniment tracks.
- Use the AR-CNN technique to modify notes in your input track.
- Use the transformers technique to extend your input track by up to 30 seconds.
## GANs with AWS DeepComposer
A GAN is a type of generative machine learning model which pits two neural networks against each other to generate new content: a generator and a discriminator.

- A generator is a neural network that learns to create new data resembling the source data on which it was trained.
- A discriminator is another neural network trained to differentiate between real and synthetic data.

The generator and the discriminator are trained in alternating cycles. The generator learns to produce more and more realistic data while the discriminator iteratively gets better at learning to differentiate real data from the newly created data.

During training, the generator and discriminator work in a tight loop as depicted in the following image.
<img width="653" alt="gr" src="https://user-images.githubusercontent.com/45710599/135932022-d5bf5604-d005-4fe5-b2b2-d55822d07382.png">

## AR-CNN with AWS DeepComposer
To train the AR-CNN model to predict when notes need to be added or removed from your input track (edit event), the model **iteratively** updates the input track to sounds more like the training dataset. During training, the model is also challenged to detect differences between an original piano roll and a newly modified piano roll.
