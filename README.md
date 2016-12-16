#Prepare Dataset Challenge

#Overview

This is the code for [this](https://youtu.be/0xVqLJe9_CY) video by Siraj on Youtube. The brainscan dataset is entirely fictional, but serves as a good example on how to prepare a dataset. Real examples do [exist](https://openfmri.org/dataset/) but, too many features to sift through for a short video. 

##Dependencies

* tensorflow (https://www.tensorflow.org/get_started/os_setup)
* numpy (pip install numpy) 


##Demo

Run the following in terminal
```
$ python softmax.py --train simdata/linear_data_train.csv --test simdata/linear_data_eval.csv --num_epochs 5 --verbose True
```

Add your own test data to test the model out.

##Challenge
The challenge for this video is to create a pokemon classifier by their type 1 (i.e fire, water, grass, etc.) using [this](https://www.kaggle.com/abcsds/pokemon) pokemon dataset on Kaggle. It will be great practice in data preparation (feature selection, cleaning, etc.) Post your github link in the comments and i'll announce the winner in the next video. Due date is December 22nd at Noon PST.

##Credits

Credits go to [Jason Baldridge](https://github.com/jasonbaldridge). I've merely created a wrapper to get people started.
