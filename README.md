# Image-Classification-using-CNN

Project Title: Human face make-up Classification
Project Description:

Q1: What do you seek to predict (Y)? 
The project we’re going to work on is about a classification problem. 
The Y to predict is whether the person is wearing make-up or not
What (X) data will you collect and use?
1000 human face images in total

Q2: What’s the relevance of your project? Try to pick a project related to current events and/or your interests. 
For the online verification process in some websites, we are asked to upload photos without wearing make-up (especially for women) but some people didn't pay attention to the instructions and uploaded photos with make-up by mistake. By establishing this detecting system, the websites can automatically filter out the improper photos and ask the customers to re-upload. When we go further, this system can be applied to the following occasions:
1. When applying for jobs like models, applicants are sometimes asked to upload photos without make-up. Hence, our model can make an effect. 
2. In some situations, like nurses at hospitals especially the ones attending patients with special diseases and high school students in China, wearing make-up isn’t always inappropriate and sometimes is even forbidden. Our model can help detect it and act as a warning/reminder to protect them from wearing makeup at inappropriate spots.
3. Some plastic surgery hospitals also need this technology for their online consulting service, which requires customers to upload photos without make-up so they can more accurately detect customers' accurate facial features.

Q3: Who will benefit from your model?
Companies who are hiring online. Schools, hospitals and plastic surgery hospitals. Official administrations which need to increase their efficiency by fast-recognition make- up face system. And it will help them save time and money.

Are you creating your own dataset?	
 Yes. We are going to create a mock dataset. We downloaded 1000 images about human faces. 500 images are with make-up and 500 images are without make-up. We will use a 80/20 split for validation for each class.
Model Description: 

Q4: What type of neural network will you use?
CNN

Q5: What baseline model will you use?
SVM Model
You must compare the performance of at least two different DL architectures.
CNN models with different number of filters and different number of convolutional layers and max pooling layers
CNN models before and after data augmentation
CNN models with different layers, sizes, dropout, batch size, activation functions etc.
