# deep-learning-architectures
M11: Assignment l Exploring Deep Learning Architectures
**Course:** Introduction to Machine Learning  
**Instructor:** Becky Deitenbeck
**Student:** Luis Lopez Martinez
**Date:** 4/7/2026

## Assignment Overview

  
## Reflection

Used mnist dataset for MLP and improved it by ensuring the validation data worked. The loss went down significantly fast.
For CNN I used the Fashon mnist Dataset where I used the nadam function and the model looked like it was over fitting.

Challenges were mostly displaying the CNN and building the RNN with IMDB dataset. The RNN took more time than the rest of the neural networks I was not as familiar with it at first but then I was able to implement the neural network. 
The Rnn took a long time to run at first using different epochs even less than 4 when using no batch size. When using batch size and using GRU instead of LMST the model was a bit faster we got similar results we went from around .95 to 93 using 3 epochs and batch size of 200. Using maxlenght sped up our model because we made all our sequences the max length of 250 that sped up the model

Sources: https://www.tensorflow.org/text/tutorials/text_classification_rnn
https://www.geeksforgeeks.org/machine-learning/introduction-to-recurrent-neural-network/
https://www.tensorflow.org/guide/keras/working_with_rnns 
https://keras.io/api/layers/reshaping_layers/flatten/ 


## How to Run

1. Clone this repository or download the notebook.  
2. Install requirements:
***pip for python or conda when using anaconda***  
   - pip install seaborn 
   - pip install pandas
   - pip install numpy 
   - pip install sklearn
   - pip install matplotlib.pyplot
   - pip install tensorflow 

4. Open the notebook in Jupyter Notebook or Environment that can open a .ipynb file 
