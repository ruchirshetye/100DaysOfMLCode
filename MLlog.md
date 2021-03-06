# 100DaysOfMLCode
Hello World! Ruchir here. This is the log file of all the Machine Learning Code/Learning I'm going to implement in the upcoming 100 days.
##
### Me in 15 seconds. :D
 
 I live in Mumbai, India.
 
Currently I'm pursuing my Bachelors degree in Computer Engineering. I grew interested in ML/AI due to the huge amount of research being done in this field. This whole revolution of Artificial Intelligence (AI) fascinates me. AI, coupled with other technologies has the power to make the world a better place. So, I decided to learn more about AI and apply these concepts to solve real world problems.</br> 
## 
**Link to My Repo :** https://github.com/ruchirshetye/100DaysOfMLCode

### Day 1: July 10, 2018 

**Today's Progress**: 1) Implemented a Neural Network(NN) in Python without using any framework.</br>
&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; 
2) Watched 3Blue1Browns video series on NN. 
                      
**Thoughts:** It's very quick easy to code a Neural Network using powerful libraries, but sometimes knowing what's going on behind the scenes is equally important. Hence implementing a NN from scratch in python has given me a better understanding of how NN's work. By watching 3Blue1Browns video series, I have got a visual understanding of the mathematical concepts used in NN. I recommend to watch his series on Neural Networks.

**Link to work:** ***Neural Network in Python :*** https://github.com/ruchirshetye/100DaysOfMLCode/tree/master/Day%201 </br>
&nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;***3Blue1brown*** : https://www.youtube.com/watch?v=aircAruvnKk
                  
**Resources** : Special thanks to Milo Spencer-Harper's medium article : https://bit.ly/1MUrHRJ

### Day 2: July 11, 2018 

**Today's Progress**: 1) Implemented a Neural Network(NN) using Keras library.</br>
&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; 
                      
**Thoughts:**  To build a sequential model of Neural Network with three layers. The Neural network can predict the probability of the customer leaving the bank. The Neural Network achieved an accuracy of 86.5%. 

**Link to work:** ***Neural Network Using Keras:***  [ANN using Keras](https://github.com/ruchirshetye/100DaysOfMLCode/blob/master/Day2/annKeras.py).
</br>

### Day 3: July 12, 2018 

**Today's Progress**: Learnt a about Convolutional Neural Networks.</br>
&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; 
                      
**Thoughts:** Convolutional Neural Network(CNN) is made up of 4 major steps. Those are 1) Convolution 2) Max Pooling 3) Flattening 4)Full Connection. The purpose of these layers is to detect features in images. A really good visual demo of CNN working in real time gave me a proper understanding of the process. Link to the [CNN demo](http://scs.ryerson.ca/~aharley/vis/)  </br>

### Day 4: July 13, 2018 

**Today's Progress**: Learnt about Cross Entropy and Softmax.</br>
&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;Got a basic idea of how LSTM and RNN work. 
                      
**Thoughts:** Consider a logistic regression produces a decimal between 0 and 1.0. For example, a logistic regression output of 0.8 from an email classifier suggests an 80% chance of an email being spam and a 20% chance of it being not spam. Clearly, the sum of the probabilities of an email being either spam or not spam is 1.0.</br>

Softmax assigns decimal probabilities to each class in a multi-class problem. Those decimal probabilities must add up to 1.0. This additional constraint helps training converge more quickly than it otherwise would.</br></br>
In Convolutional Neural Networks after you apply the softmax fucntion its is prefrerred to use a Cross Entropy function which basically acts as a cost function. 
</br>

### Day 5: July 14, 2018 

**Today's Progress**: 1) Implemented a Convolutional Neural Network(NN) using Keras library.</br>
&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; 
                      
**Thoughts:** Trained the CNN on images of dogs and cats. The architecture of the CNN used was Conv2d->MaxPooling2D->Flattening Layer->One Fully Connected Layer->Output(2 Classes). It took a total time of 8-9Hrs to train itself. The results after train were not satisfactory. The model had overfitted itself. The accuracy on the training set was 99.5% (loss = 0.0145)and the test set accuracy was 74.84%(val_loss = 2.2570).I have planned to improve this model by adding more hidden layers or using regularization function. Note that
Image Augmentation technique was also used, but wasn't sufficient to reduce the overfitting.

**Link to work:** ***Neural Network Using Keras:***  [CNN using Keras](https://github.com/ruchirshetye/100DaysOfMLCode/blob/master/Day%205/cnn.py).

### Day 6-7: July 15-16, 2018 (Dimensionality Reduction)

**Today's Progress**: 1) Implemented Principal Component Analysis algorithm using Python and R.</br>
&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; 
                      
**Thoughts:** Principal Component Analysis is used for feature extraction. It's one of a dimensionality reduction technique.
I used PCA on a dataset which consists of 12 different wine properties. The dataset has been classified into 3 customer segments.
After applying PCA on this dataset, I got an insight of how these 12 features were contributing towards the variance. Hence by selecting the top 2 contributors and applying logistic regression to the reduced dataset, I got an accuracy of 97.2%. 

**Link to work:** ***PCA using Python and R:***  [PCA](https://github.com/ruchirshetye/100DaysOfMLCode/tree/master/Day%206-7).

### Day 8: July 17, 2018 (Dimensionality Reduction)

**Today's Progress**: 1) Implented Linear Discriminant Analysis(LDA).</br>
&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; 2)Implemented Kernel PCA                      
**Thoughts:** 1)Logistic regression is a classification algorithm traditionally limited to only two-class classification problems.
If you have more than two classes then Linear Discriminant Analysis is the preferred linear classification technique. LDA is a supervised algorithm as it takes the class label into consideration. It is a way to reduce ‘dimensionality’ while at the same time preserving as much of the class discrimination information as possible.</br>
2)Kernel PCA just performs PCA in a new space. It uses Kernel trick to find principal components in a different high dimensional space.

**Link to work:** ***LDA and Kernel PCA using Python:***  [CODE](https://github.com/ruchirshetye/100DaysOfMLCode/tree/master/Day%208).
                  
### Day 9: July 18, 2018 (Model Selection)

**Today's Progress**: 1) Learnt how k-fold cross validation works.</br>
&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;

**Thoughts:** Cross-validation is used to evaluate machine learning models on a limited data sample.
The procedure has a single parameter called k that refers to the number of groups that a given data sample is to be split into.This procedure is often called k-fold cross-validation. When a specific value for k is chosen, it may be used in place of k in the reference to the model, such as k=10 becoming 10-fold cross-validation.
Cross-validation is primarily used in applied machine learning to estimate the skill of a machine learning model on unseen data. That is, to use a limited sample in order to estimate how the model is expected to perform in general when used to make predictions on data not used during the training of the model.

**Link to work:** ***k-fold cross validation applied on SVM classification model:***  [CODE](https://github.com/ruchirshetye/100DaysOfMLCode/tree/master/Day%209).

### Day 10: July 19, 2018 (Model Selection)

**Today's Progress**: 1) Learnt how Grid Search works.</br>
&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;

**Thoughts:** Hyper-parameters are parameters that are not directly learnt within estimators. Typical examples include C, kernel and gamma for Support Vector Classifier. The traditional way of performing hyperparameter optimization has been grid search, which is simply an exhaustive searching through a manually specified subset of the hyperparameter space of a learning algorithm. A grid search algorithm must be guided by some performance metric, typically measured by cross-validation on the training set.

**Link to work:** ***Grid Search applied on SVM classification model:***  [CODE](https://github.com/ruchirshetye/100DaysOfMLCode/tree/master/Day%2010).



### Day 11-12: July 20-21, 2018 

**Today's Progress**: 1) Implemented XGBoost.</br>

&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;
2) Tried Google Colab( Google's free cloud service for AI developers) for training CNN model.</br>
**Thoughts:** XGBoost is a software library that you can download and install on your machine, then access from a variety of interfaces.
The two reasons to use XGBoost are execution speed and model performance.

**Link to work:** ***XGBoost:***  [CODE](https://github.com/ruchirshetye/100DaysOfMLCode/tree/master/Day%2011-12).

### Day 13: July 22, 2018 (Reinforcement Learning)

**Today's Progress**: 1) Implemented Upper Confidence Bound.</br>

&nbsp;&nbsp; &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;
**Thoughts:** Upper Confidence Bound is a reinforcement learning algorithim. It is used to maximize your returns.Initially you have no idea what is the optimal distribution of your returns on your investments, for eg Ads,Bandit Machines. When you have 10 versions of a ad  for your website but are not quite sure of which ad will give maximum returns.Then UCB algorithm can help you. You can solve this problem with A/B testing but for that you need to explore the possiblities and then exploit them. Instead of this we can combine exploration and exploitation to get the optimal results as soon as possible. This can be done by upper confidence bound algorithm.

**Link to work:** ***Upper Confidence Bound:***  [CODE](https://github.com/ruchirshetye/100DaysOfMLCode/tree/master/Day13).


### July 23 - August 14 , 2018 

**Update** : Will start updating my daily work from tomorrow. During this period,I was busy with a lot of college related work and campus placement process, so couldn't update the repo everyday, but I did watched some videos of Siraj Raval on Decentralized Application and Computerphiles videos regarding deep learning. Will resume my journey tomorrow.

### Day 14: August 15, 2018

Hey! I know, I know I have taken a long break in between and might have broken the first rule of this challenge which is doing something related to AI everyday. Eventhough I am late, I'll make sure I complete this challenge without taking any breaks in the future.Let's hope for the best. The remaining 85 Days here I come! :P </br>

**Today's Progress**: 1) Started with fast.ai's deeplearning curriculum.</br>
 
**Thoughts:** Fast.ai follows a top-down approach for learning which means it will give you a high level understanding on the topic and gradually will go deep in that specific topic.In Lesson 1, we started with training a Cats vs Dogs Classifier which used transfer learning from the Resnet architecture and also gave a high level understanding of how CNN layers learn. A overview of Jupyter Notebook was also given in Lesson 1.Then in Lesson 2,I learned about learning rate finder.Also concepts such as Data Augmentation, Stochastic Gradient Descent with Restarts and Fine Tuning models were explained. Overall got to learn a lot of things in the first 2 Lessons itself. Hope to learn a lot from this course. 

**Link:** ***fast.ai:***  [fast.ai(Lesson1)](http://course.fast.ai/lessons/lesson1.html).
[fast.ai(Lesson2)](http://course.fast.ai/lessons/lesson2.html)

### Day 15: August 16, 2018

**Today's Progress**: 1) Continued with fast.ai's deeplearning curriculum.</br>
 
**Thoughts:** Got more in-depth knowledge on training CNN Classifier.Completed Lesson 2 of fast.ai.

**Link:** ***fast.ai:***  [fast.ai(Lesson2)](http://course.fast.ai/lessons/lesson2.html)

### Day 16: August 17, 2018

**Today's Progress**: 1)Started a Kaggle Dog Breed Classifier Kaggle competition .</br>
 
**Thoughts:** This is similar to Dogs Vs Cats Classifier using CNN. The model will be Trained on Resnet Architecture.

**Link:** ***fast.ai:***  [fast.ai(Lesson2)](http://course.fast.ai/lessons/lesson2.html)
***Kaggle Competition***  [Kaggle](https://www.kaggle.com/c/dog-breed-identification)

### Day 17: August 18, 2018

**Today's Progress**: 1) Tried New York City Taxi Trip Duration Prediction on Kaggle.</br>
 
**Thoughts:** The dataset contains features like Co-ordinates of pick and drop location, time takent to complete the trip , area , time of pickup and drop and many more. Will train it in Google Colab. It's not yet complete. Will update once completed.

**Link:** ***Kaggle Competition***  [Kaggle](https://www.kaggle.com/c/nyc-taxi-trip-duration)
