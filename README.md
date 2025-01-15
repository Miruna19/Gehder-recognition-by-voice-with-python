# Gehder-recognition-by-voice-with-python

## About project
In this project, we aim to perform speaker gender detection. The human voice represents a signal with infinite information; in addition to emotions and dialect, we can also identify a person's gender using the vocal characteristics of the signal.

## The dataset

Reference:
https://www.kaggle.com/datasets/primaryobjects/voicegender

https://www.atlantis-press.com/article/25868884.pdf

The code presents a pre-existing database, which includes 20 parameters extracted from voice samples, offering insight into the acoustic characteristics of the human voice. The database contains several voice samples, each of which is actually a .WAV file. The files have been preprocessed for acoustic analysis. The preprocessed WAV files have been saved in a CSV file. The file contains 3.168 rows and 21 columns. The 21st column indicates the gender, either male or female.

## Software Libraries

-  TensorFlow
-  Numpy
-  Pandas
-  Sklearn
-  PyDub
-  Wave
-  IPython
-  Librosa

  ## **Data Preprocessing**

The LabelEncoder class from the sklearn library is used to transform the values of the labels, i.e., the "label" column, from text format to numeric format. Using the `fit_transform` method, the LabelEncoder model is adjusted to the "label" column, and the labels are transformed into numeric values. The `fit_transform` method is applied to the "label" column because we want to convert the gender labels, "female" and "male", into numeric values. Therefore, the "female" label will be transformed into the numeric value 0, and the "male" label will be transformed into the numeric value 1.
  
