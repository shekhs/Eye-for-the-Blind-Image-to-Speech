# Eye-for-the-Blind
## Image-to-Speech
A deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on *[Flickr8K dataset](https://www.kaggle.com/adityajn105/flickr8k)*.

## Motivation##
##
The project is an extended application of *[Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/abs/1502.03044)* paper.

## Dataset


*[Flickr8K dataset](https://www.kaggle.com/adityajn105/flickr8k)*. 

The dataset is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

## Pipeline

*Data Understanding* loading the data and understand the representation.  

*Data Preprocessing* processing both images and captions to the desired format.  

*Train-Test Split* Combining both images and captions to create the train and test dataset.  

*Model Building* create the image captioning model by building *Encoder, Attention and Decoder model.*. 

**Model Evaluation**: Evaluate the models using **greedy search** and **[BLEU score](https://cloud.google.com/translate/automl/docs/evaluate#:~:text=BLEU%20(BiLingual%20Evaluation%20Understudy)%20is,of%20high%20quality%20reference%20translations.)**.

## Steps
 - Download the Flickr8k dataset. This will contain a captions file and an Images folder.   0
 - Unzip the contents in root directory.  
     - Place in Images folder in root directory.  
     - Captions file should be placed in root directory as well.  
 - Run the notebook after installing all dependencies.  
 - The notebook will generate a wav file explaining the image contents. 
 
