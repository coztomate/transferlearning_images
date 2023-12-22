# Webscraping, Transfer Learning and Feature Extraction for Cat Breed Classification

## Overview
This repository presents a Cat Breed Classifier designed to distinguish among 19 different cat breeds, surpassing the variety found in existing classifiers which typically recognize 12-15 breeds. This project was inspired by the most popular cat breeds listed by the [Cat Fanciers’ Association](https://www.forbes.com/advisor/pet-insurance/pet-care/popular-cat-breeds/), focusing on the top 20, and excluding the non-pedigreed domestic cats, thus arriving at 19 distinct breeds. 

## Data Collection
The data for this project was derived by scraping images from DuckDuckGo search results for each of the 19 cat breeds. Each image underwent visual inspection to ensure quality.

## Methodology
Utilizing TensorFlow and the power of transfer learning, the model is built upon the MobileNetV2 architecture, known for its efficiency and effectiveness in mobile vision applications. Additional dense layers were integrated, culminating in a softmax classification layer  designed for this 19-class classification task. The model has achieved an accuracy of 85%.

## Repository Contents
- **WebScraping Notebook:** Details the process of collecting and cleaning the image data from DuckDuckGo.
- **Training Notebook:** Provides a comprehensive guide to the training process, including model architecture and performance metrics.

## Getting Started
To get started, simply open the notebooks in Colab. Please note that a connection to your Google Drive is required for data storage and retrieval.

## Future Work
The project is a work in progress with plans to enhance its capabilities further. Future updates include:
- Ensembling models to improve prediction accuracy.
- Expanding the classifier to recognize all cat breeds as acknowledged by the World Cat Federation.

## License
This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
