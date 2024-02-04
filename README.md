# Hello Convolutional World 
My First Deep Learning Project on my own 

## Objective
- Learn How the different layers and parameters affect Performance for a classic Convolutional Network. Search for common values within the literature Specifically:
  - Pooling and standard convolutional architecture (Conv, Pool, FC) More convolutional, or more FC? 
  - Strided convolutions. How do they relate computational cost and performance? 
  - Padding. How does it relate computational cost and performance? 
  - 1x1 convolutions. 
  - Filter size
  - Normalization
  - Residual conections
  - Depthhwise separable convolutions

- Use error analysis to analyse model performance
  - Visualize the data the model is failing on. Can something be done?
  - Simulate an easy to solve problem with error analysis: All orange will be from cats, no orange-yellow-ish dogs.

- Build a image classification model having learnt what it is above. Preferably one kaggle competition, both in torch and tensorflow
  - It will be needed an additional fine tunning for the learning rate hyperparameter.

## Structure
- Input: obtain/store data
- src: all script py files
- models: all trained models 
- notebooks: all stored notebooks

## Restrictions throught all the project
- Models can not be bigger than 50K parameters. Its not important to get the best results, but to iterate quickly. as the first experiments are carried out this value might be decreased. 
- Standarized learning rate of 0.0001. This is for the sake of simplicity. 