<a name="readme-top"></a>


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/onlyEugeneLi/Engagement_Prediction">
    <img src="images/pepper-logo.jpg" alt="Logo" width="300">
  </a>

  <h3 align="center">Machine Learning for Pesonalised Robotic Service in Cafés</h3>

  <p align="center">
    This project is part of my dissertation for a Master's degree.
    <br />
    <a href="https://github.com/onlyEugeneLi/Engagement_Prediction"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/onlyEugeneLi/Engagement_Prediction">View Demo</a>
    ·
    <a href="https://github.com/onlyEugeneLi/Engagement_Prediction/issues">Report Bug</a>
    ·
    <a href="https://github.com/onlyEugeneLi/Engagement_Prediction/issues">Request Feature</a>
  </p>
</div>

[**For Multimodal Learning models training visualisations and code, please access here.**](https://github.com/onlyEugeneLi/Engagement_Prediction/blob/main/Multimodal_Engagement_Prediction.ipynb)<br>

[**For multimodal feature importance assessment, please access here.**](https://github.com/onlyEugeneLi/Engagement_Prediction/blob/main/Single_Modal_Engagement_Prediction.ipynb)<br>


## About the project

Let's consider a marketing agent. The products that they would recommend will be based on their inferences of the customers they are interacting with. 

Such inferences include their gender, age, whether they are a family or a group of friends.

Similarly, the robots should be able to infer user profiles to make suitable recommendations. We will explore techniques to identify customer's profile to adapt robot's behaviours. The project will aim to profile users based on these characteristics (one or two of them) automatically.

And a proof-of-concept robot dialogue will be implemented to evaluate the personalisation of the dialogue based on the user profile.

**A glance at the data distribution**
<img src="images/newplot (1).png" width="800"/>

**Undersampling to enhance the classification decision boundary**
<img src="images/newplot.png" width="800"/>

### Pepper--Social Robot Applied in Human-Robot Interaction experiments

<img src="images/pepper.png" width="400"/>

Background, brief introduction

### Experiment setting

**Third-person Perspective of the Interaction in the cafe**

<img src="images/experiment.png" width="400"/>

**Real-time Visual Signal Received from Pepper's Perspective**

<img src="images/pepper-view.png" width="400"/>

### Feature Representation

* **Body posture**

<img src="images/body-pose-feat.png" width="400"/> 
<img src="images/recog_main_subj_skel_plot.png" width="600"/>

* **Head Pose and Eye Gaze**

<img src="images/face-feat.png" width="1000"/> 

* **Emotion Recognised from Facial Expression**

  
  <img src="images/py-feat.png" width="700"/> 
  <img src="images/emo.png" width="400"/> 

### Results

<img src="images/svm_cm.png" width="400"/> <img src="images/rf_cm.png" width="400"/>

<img src="images/f1-scores.png" width="800"/>

## Next steps

* Understand SVM
* Identify potential tricks to counteract imbalanced data
* Test on each them
* Visualise data based on features

## Choosing ML models

* SVM: SVMs are particularly well suited for classification of complex but small- or medium-sized datasets.
* Random Forest

## Objectives

* Train 2 / 3 models: SVM, Random Forest, Simple NN if still enough time
* Data imbalance: SMOTE, Weight
* Evaluation: Cross validation
* Visualisation
