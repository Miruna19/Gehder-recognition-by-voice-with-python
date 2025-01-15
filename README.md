
# Gender-recognition-by-voice-with-python


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

## Preparing the dataset for training and evaluating the model



## 	Artificial Neural Network

For the implementation of the project, artificial neural networks were used with the help of the TensorFlow library. A fully connected neural network (Fully Connected Neural Networks) was utilized, which is a type of artificial neural network where every neuron in a layer is connected to every neuron in the previous layer. This was achieved by using Dense layers in TensorFlow.

An artificial neural network consists of 3 layers:

1. **Input Layer**
2. **Hidden Layers**
3. **Output Layer**

The hidden layers contain multiple activation functions. Activation functions are simply mathematical methods that convert values into a range between 0 and 1. In our case, the ReLU and Sigmoid activation functions were used.


  
