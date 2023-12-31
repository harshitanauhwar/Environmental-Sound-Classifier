# Environmental-Sound-Classifier
This project's main goal is to create a machine learning model that can identify Capuchin bird calls. Sound extracts from various datasets, a  convolutional neural network model, and audio data augmentation techniques will all be used to identify the same.
Although music and speech signals have been the focus of audio recognition research for long, environmental sound recognition (ESR) has recently drawn increased 
attention. Over the past ten years, there has been a marked surge in ESR research.

Specifically, Bird Call Classification was performed to count the number of a certain bird call in a recording and train a TensorFlow model to apply it to the Forest Sound 
Recordings and identify the same. The project includes model implementations of Conventional Neural Network using 
TensorFlow. Matplotlib is used for Visualization Purposes. Converting Audio  Classification to Image Processing helped conclude the number of birdcalls

**Data Acquisition** was done using **Public Datasets obtained from Kaggle**.

About the Dataset:
The data is divided into Training and Testing Data. 

1. **Testing Set:**

[a] Forest Recordings - These are the Recordings to use to count the number 
of Calls within. Each clip is ~3 min and includes a mix of Capuchinbirds and 
other sounds.
  -  Contains 100 files

2. **Training Set**

[b] Parsed_Capuchinbird_Clips - These are parsed 3 sec clips that include 
specific bird calls from Capuchinbirds only
  -  Contains 217 files
    
[c] Parsed-Not-Capuchinbird_Clips - These files are parsed sounds from other 
animals/birds that are useful in training what is not a Capuchinbird.
  - Contains 593 files
