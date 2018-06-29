# languageModelling
This application, written in Python, aims at Generating a sequence of characters in English using Recurrent Neural Networks!

## Getting Started 

### Prerequisites

This application was built using: 

    Python 3.6, jupyter notebook 4.3.1, Tensorflow 1.8

### Dataset 

Data set for this Application can be downloaded as [here](http://www.gutenberg.org/cache/epub/2265/pg2265.txt):

    - For MacOS or Linux: Run the following command in the terminal:
                          curl http://www.gutenberg.org/cache/epub/2265/pg2265.txt > pg2265.txt
                          
    - For Windows: Directly save the file from above link
    
### File Description

    * pg2265.txt: This file contains the data that is used by our model(Recurrent Neural Network)
    
    * languageModel_RNN.ipynb: This file contains all the necessary code for Generating Character Sequences in English using a 
                               Recurrent Neural Network
                               
    * model-20: This folder contains the parameters learned by of our model during training. This is restored later to generate
                text sequences
    
                        
