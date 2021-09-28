# Custom Trash Detector Using AWS DeepLens 
In this project, we use an AWS DeepLens device to do an image classification–based task. We train a model to detect if a piece of trash is from three potential classes: landfill, compost, or recycling.
## Summary
Four key components are required for an AWS DeepLens–based project.
1. **Collect your data:** Collect data and store it in an Amazon S3 bucket.
2. **Train your model:** Use a Jupyter Notebook in Amazon SageMaker to train your model.
3. **Deploy your model:** Use AWS Lambda to deploy the trained model to your AWS DeepLens device.
4. **View model output:** Use Amazon IoT Greenrass to view your model's output after the model is deployed.
## Machine Learning workflow
1. **Define the problem.**
   * Using machine learning, we want to improve how trash is sorted. We're going to identify objects using a video stream, so we identify this as a computer vision–based problem.
   * We have access to data that already contains the labels, so we classify this as a supervised learning task.
2. **Build the dataset.**
   * Data is essential to any machine learning or computer vision–based project. Before going out and collecting lots of data, we investigate what kinds of data already exist and if they can be used for our application. 
3. **Train the model.**
   * Now that we have our data secured for this project, we use Amazon SageMaker to train our model. 
4. **Evaluate the model.**
   * Model training algorithms use loss functions to bring the model closer to its goals.
   * The loss function improves how well the model detects the different class images (compost, recycling, and landfill) while the model is being trained. 
5. **Use the model.**
   * We deploy our trained model to our AWS DeepLens device, where inference is performed locally. 
