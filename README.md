# Bird_Species_Classification

This is a project developed for the curricular unit of Soft Computing.

## Problem Statment
_Classify the bird species that appear on an image based on the use of a Convolutional Neural Network
model (CNN)._

## Learning Objectives
- Preparation and analysis of dataset;
- Training and validation of learning models, specifically Convolutional Neural Networks (CNN);
- Use of Genetic Algorithms (GA) for learning model hyper parameter optimization, structure
optimization and loss function optimization.


## Dataset

The proposed dataset has the following features:
- **Bird Species**: 250
- **Training Images**: 35215 (not balanced, however has at least 100 training image files per
species);
- **Validation Images**: 1250 (5 per species);
- **Test Images**: 1250 (5 per species);
- **Images Size**: 224 x 224 x 3 color channels in jpg format;
- **Species gender**: 80% of total images are of male while the remaining 20% are of female - the classifier may not perform as well on female specie images.