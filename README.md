# Machine Learning Notebooks

Housing for ML notebook tutorials. Goal is to write more in depth explanations as text tutorials and use some of the notebooks below for demonstration. 

## Neural Networks (Tensorflow2)

The below notebooks are written using Tensorflow 2.1.

Current notebooks:

  1. Shrekining.ipynb
  2. TimeSeriesModelling.ipynb
  3. VAE.ipynb
  4. ObjectDetection.ipynb
  
#### Shrekining.ipynb

A notebook demonstrating how a Shrek movie script can be generated using an RNN. 

<a href="https://colab.research.google.com/drive/1vTYdkHLi4mHXjM6jr005m0ObvX50AYOl">Open in Google Colab</a>

#### TimeSeriesModelling.ipynb

A notebook demonstrating time series modelling using windowed datasets in TF. 
The model accepts any combination of 14 input features to predict an output over a specified window of time.

<a href="https://colab.research.google.com/drive/1GKHv6DTKawzEWoTNXnM1LTZufVhzqJ5f">Open in Google Colab</a>

#### VAE.ipynb

A notebook demonstrating a Convolutional Variational AutoEncoder over numerous TF datasets. The model accepts both RGB and 
grayscale datasets. The model can save the input/reconstructed  outputs and generated images as gifs for easy 
visualization. The notebook contains gifs/images of the model generating and reconstructing flowers, Japanese letters, 
horses and humans and even Donald Trump.

<a href="https://colab.research.google.com/drive/1QFmbOz8IQFOTyzQxfQYCoLDQ36rYw0By">Open in Google Colab</a>

#### ObjectDetection.ipynb

A notebook covering easy object detection through the use of TF Hub. The theory and evolution behind the FasterR-CNN model (R-CNN ==> FastR-CNN ==> FRCNN) 
is discussed prior to loading the model and performing detection.

<a href="https://colab.research.google.com/drive/1o0_ULEQgm1Zev_WsH-loSH61eadBciVd">Open in Google Colab</a>

## Trees

Current notebooks:

  1. Forests4Forests.ipynb

#### Forests4Forests.ipynb

A notebook exploring decision trees, random forests and gradient boosting trees (using xgboost) on a forest dataset (predicting trees with trees  :stuck_out_tongue_winking_eye:).

<a href="https://colab.research.google.com/drive/1avx60B63DBaNLiTTv3SPZDSaaIFMXllV">Open in Google Colab</a>

## ML Concepts

Current notebooks:

  1. DimReduction&Proj.ipynb
  2. 1CyclePolicy.ipynb

#### DimReduction&Proj.ipynb

A notebook exploring 4 dimension reduction techniques (2 linear, 2 manifold) on toy sklearn datasets. Projections are made into 2D and 3D spaces to see strengths/weaknesses of the methods.

<a href="https://colab.research.google.com/drive/11RL8cFnpsKxjJJshCumI7zBvDdyNLo9B">Open in Google Colab</a>

#### 1CyclePolicy.ipynb

A notebook exploring the 1-cycle learning policy introduced by Leslie Smith <a href="https://arxiv.org/abs/1708.07120">here</a>.

<a href="https://colab.research.google.com/drive/1jG4-A01_HdO-KZPu8oeACM8as_FZ0c5C">Open in Google Colab</a>

## DS Concepts

### AccidentalDrugDeaths

Notebooks:

  1. DataCleaning.ipynb
  2. DataVisualization.ipynb
  
### TrumpTweets

Notebooks:

  1. SentimentalTrump.ipynb

#### SentimentalTrump.ipynb

Trumps tweets since 2009 were downloaded for sentiment analysis over the years.

(IN PROGRESS)

#### DataCleaning.ipynb

A notebook covering data cleaning and preparation prior to visualisation. The dataset used is the Accidental Drug Deaths from <a href="https://catalog.data.gov/dataset">data.gov</a>. The notebook covers setting new indices, dropping unwanted columns, cleaning the data using lambda maps, extracting parts of data using regular expressions, detecting and handling missing data, dropping rows based on column criterion and looking at word frequencies to determine possible classes for a column.

#### DataVisualization.ipynb

A notebook covering data visualization for the Accidental Drug Deaths dataset. We explore how to plot results, reordering the results so we may plot in ascending/descending order, looking at class dominances, looking at trends between age/sex and year in the relation to overdose count, amongst other relationships between the data. 

## TF Certification

Google have launched <a href="https://www.tensorflow.org/certificate">TF certification</a>. The exam is spread across 5 categories:

  1. Basic / Simple model
  2. Model from learning dataset
  3. Convolutional Neural Network with real-world image dataset
  4. NLP Text Classification with real-world text dataset
  5. Sequence Model with real-world numeric dataset
  
This <a href="https://www.coursera.org/specializations/tensorflow-in-practice">course</a> is cited as the advised preparation for the exam, it is split into 4 parts. The notebooks below cover the various aspects of the course. These are not complete tutorials, but more study notes.

  1. DL_part1.ipynb - Part 1 : Category 1 & 2
  2. DL_part2.ipynb - Part 2 : Category 3
  3. DL_part3.ipynb - Part 3 : Category 4
  4. DL_part4.ipynb - Part 4 : Category 5
  
#### DL_part1.ipynb

Notebook covering the basics of the TF specilization course, part 1, weeks 1 - 4. Includes training a simple model to estimate a linear function, using learning datasets and visualizing convolution outputs.

<a href="https://colab.research.google.com/drive/12sw0DfFxHdW-B4L_o079lKaeR1sKL-cz">Open in Google Colab</a>

#### DL_part2.ipynb

Notebook covering CNNs on real-world image datasets. Topics include data augmentation, dropout and transfer learning.

Note: To practice on real-world datasets, one can use the following <a href="https://www.kaggle.com/general/74235">guide</a> for downloading kaggle datasets in colab.

<a href="https://colab.research.google.com/drive/1g4bkiHLhgXB7-mAg7D2kUlnShU6rOxbW">Open in Google Colab</a>

#### DL_part3.ipynb

Notebook covering Natural Language Processing. Topics include text preparation, text classification, visualization and text generation. 

Note: Character level prediction is omitted from this notebook, however it is covered in the Shrekining.ipynb notebook above.

<a href="https://colab.research.google.com/drive/1F1-A1Tup2lL3xDecKedJEDDDJvmVxxL_">Open in Google Colab</a>

#### DL_part4.ipynb

Notebook covering time-series modelling, including how to prepare the data using TF windowing, learning rate scheduling as well as the structure of an effective temporal model.

Note: The notebook covers predicting the following time step from a previous window. To see how we may predict a window in the future from a previous window please make reference to the TimeSeriesModelling.ipynb notebook above.

<a href="https://colab.research.google.com/drive/1GUUt2eNUksEHoaoZ3T0Rw2Ee-qVI4XfQ">Open in Google Colab</a>



 
