# deeplearning
Deep learning Project 

The repository contains a notebook for task 1. This notebook includes a 1D-CNN to annotate protein sequences and determine whether they perform a certain function or not. The code contains multiple modifications to the hyperparameters to improve the performance of the model to return a high test accuracy and a low test error. Some of the modifications to the hyperparameters include changing learning rates, dropout rates, weight decay and trying a different optimizer (SGD) to test effect of changing the momentum. 
Furtermore, some modifications were also made to the architecture to further improve the performance. This architectural changes include adding a batch normalization and changing the kernel size. 

Task_a_validation_set python notebook contains code to building the 1D-CNN with the help of simulated datasets. It includes evaluating the performance of the model by chaning various hyperparameters. The notebook contains 2 CNN models, one without batch normalisation and one with batch normalisation to see the effect of batch normalisation. 
The performance of the model was also tested on another simulated dataset containing protein sequences of much longer lengths. 
To visualise the performance, graphs have been plotted of the losses and accuracies of the training, validation and test sets. 

The testing_with_GO_annotations python file includes running the model on the given GO annotation terms. The model was used to test how it performs on a real protein sequence dataset. To evaluate the performance of the model on the different GO terms, various metrics were used. 
The notebook also includes running the model on human protein sequence data and testing the performance of the model on this dataset. 

The confusion matrices, classification reports and accuracies may not match the ones reported in the report due to the randomisation parameter when splitting the dataset in training, validation and testing datasets. 
