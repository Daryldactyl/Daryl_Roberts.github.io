---
title: "Capuchin Bird Classification and Application to Derive Population Density"
excerpt: "This project built a convolutional neural network model to identify Capuchin bird calls in forest recordings using audio spectrograms, achieving 100% accuracy and enabling automated analysis of ecological data."
collection: datascience
---
## Check out the project [here](https://github.com/Daryldactyl/Capuchin_bird/blob/main/Audio_class.ipynb)
## Tools Used
*TensorFlow, Keras, Convolutional Neural Networks, Data Preprocessing, Audio Data Processing, Resampling, Padding, Spectrogram Generation, Librosa, Time Series Data Handling, Custome Data Augmentation, Model Building, Model Training, Model Evaluation, Visualizing Model Performance, Visually Analyze Model Output, Function Creation, Script Development, Machine Learning, Data Analysis, Data Interpretation, CSV file Creation*
## Summary:
- **Deep Learning Model Development and Data Preprocessing:**
Leveraged TensorFlow and Keras to build a convolutional neural network (CNN) model. Librosa facilitated audio data preprocessing by resampling to a consistent rate (16 kHz) and generating spectrograms for model input. Zero-padding functions were developed using TensorFlow to address variable audio clip lengths, ensuring consistent model training.

- **Time Series Data Handling and Model Training:**
Utilized TensorFlow's timeseries_dataset_from_array function to prepare audio data as time series sequences for model training. The trained model was then evaluated on a held-out test set using metrics like accuracy, precision, and recall.

- **Forest Recording Analysis and Result Reporting:**
Processed forest recordings with the trained model to predict Capuchin bird call presence. Predictions were analyzed to identify recordings with the highest number of calls. Finally, results were exported to a CSV file for further exploration.

- **Technical Skills Demonstrated:**
Proficient in TensorFlow and Keras for deep learning model development and training. Expertise in data preprocessing techniques using librosa for audio analysis. Familiarity with time series data handling and evaluation metrics for classification tasks. Skilled in Python programming libraries for data manipulation, model building, and result reporting.
