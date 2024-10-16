# EEGEmotionRecognition

This project was the symposium project for my high school Advanced AI course. 
It is a model that classifies brain EEGs (signals measuring electrical activity in the brain) with a corresponding emotional state (positive, negative, or neutral). 
This dataset didn’t require preprocessing of raw EEGs, which was a big part of my previous EEG project. Instead, the dataset I used came with already cleaned and processed data, so the main component of this project was building the model to classify. 
The final goal for this project was to extend this model's application to individuals with Autism Spectrum Disorder, providing support and enhancing well-being through improved emotional regulation/social skills within this user-group.

My process consisted of: 
  Exploratory data analysis
  Standard scaling
  MLP model
  Neural network
  Model evaluation
The MLP (based on the papers linked below) and feedforward neural network reached around 94% and 97% accuracies for each model respectively. 

Dataset: 
https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions/data 

Papers: 
https://www.researchgate.net/publication/329403546_Mental_Emotional_Sentiment_Classification_with_an_EEG-based_Brain-machine_Interface 
https://www.researchgate.net/publication/335173767_A_Deep_Evolutionary_Approach_to_Bioinspired_Classifier_Optimisation_for_Brain-Machine_Interaction 
