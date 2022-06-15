# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

  This project is for Multiclass Melanoma Detection for neural networks
- What is the background of your project?

  Convolutional Nueral network to identiyfy Melanoma from the images provided
- What is the business probem that your project is trying to solve?

  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It    accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the dataset that is being used?
 
  This assignment uses a dataset of about 2357 images of skin cancer types. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis

  The model is over fitting as we can see differnce in training and test
- Conclusion 2 from the analysis

  There is no improvement in accuracy but we can definitely see the overfitting problem has solved due to data augmentation
  We can increase the epochs to increase the accuracy so it's too early for judgement
- Conclusion 3 from the analysis
  
  Seborthiec keratosis has least number of samples
  Base cell carcinoma,nevus have proportionate number of classes. melanoma and pigmented benign keratosis have proprtionate number of classes
- Conclusion 4 from the analysis
  
  Accuracy on training data has increased by using Augmentor library  
  Model is still overfitting
  The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.
  The Model can be further improved by tuning the hyperparamete
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- Keras, Tensorflow and Augmentor
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
