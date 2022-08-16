# Meolnoma Detection using CNN
> This project envisage to detect Melonoma from photographs of skin.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project envisage to use CNN to classify the skin photographs into various categories of diseases.
- What is the background of your project?
  - Early detection of Melonoma may enable better treatment and early cure of Melonoma. The project is to classify the disease from skin photos.
- What is the business probem that your project is trying to solve?
-   Early detection of disease
- What is the dataset that is being used?
  - The dataset used is Skin cancer ISIC The International Skin Imaging Collaboration provided by IIIT B 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
  - Training Accuray is 93.5% with and validation accuray is 96.64%
  - The model is clearly overfitting.
  - Dropout layer was not added to the inital model.
  - Training and validation loss are moving in sync.
- Conclusion 2 from the analysis
-Use of augumentaion has solved the isseu of overfitting.
 - However, the accuracy has reduced considerably to 62% for training and 65% for validation. It seems model is now gone to     underfitting from overfitting.
  - The accuracy for taining and validation are in similar range.
- Conclusion 3 from the analysis
  -The class with least number of samle is Senorrheic Keratosis with just 77 samples that account for just 0.34% of whole data.
  - Dominant Class: Pigmented Benign Keratosis with 462 samples that account for 20.6 % data.
- Conclusion 4 from the analysis
  - Final model is good fit with 74 % training accuracy and 70% validation accuracy.
  - Correcting the class imbalance has improved the model performance considerably.
  - Increasing Epochs may give better accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by
  - Use of CNN for melonoma Detection
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@JoeJacob2755] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->