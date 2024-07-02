# BeHealthy - Disease Treatment Prediction

BeHealthy is a health tech company which provides medical services, prescriptions and online consultations and generating huge data day by day. Medical data is generated when a doctor is writing notes to his/her patient or as a review of a therapy that he or she has done. There are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text. The aim of this project is create a custom NER to determine the disease name and its probable treatment from the dataset. 

## Table of Contents
* [General Info](#general-information)
* [Project Statement](#project-statement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)

## General Information

Medical data generated out of doctors' notes contain details about diseases and their related treatments. This information is not explicitly mentioned in the dataset about the diseases and their treatment, but, we can build an algorithm to map the diseases and their respective treatment(s).

## Project Statement

To build a custom NER to accurately predict treatment for a given disease.

## Technologies Used

Python 3.x, 
pycrf 0.0.1,
scikit-learn 0.24.0,
spaCy

## Conclusions

- Solutions accuracy is nearly 90% on test set
- The model was able to detect the treatment of many diseases
- The model's accuracy can be further improved if we get larger dataset for training and testing

## Acknowledgements

This project was inspired by UpGrad IIITB study Programme as a case study for the Machine Learning & AI Program-October 2023 Course.

## Contact

Created by Sanat Srivastava

## License

This project is open source and available without any restrictions.
