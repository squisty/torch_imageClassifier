# Classifying Cat Breeds using PyTorch and DenseNet

This project is based on curriculum that I learned in the Master of Data Science Program at the University of British Columbia. I used data from Kaggle which contained around 1500 images of six different cat breeds and compared convolutional neural network (CNN) models to determine which ones would work the best. The metrics I used for scoring were time to train and valid accuracy. Overall, the DenseNet model worked best when I added and tuned a few layers on top of the base model to account for only six possible outputs and achieved a valid accuracy of .95 after 20 epochs of training. However, all of the DenseNet models that I tested took quite a bit longer to train than my CNN from-scratch model. The worst model was the one that I created from scratch which only achieved a valid accuracy of .41 after 5 epochs of training but was much faster at training than the DenseNet model.
