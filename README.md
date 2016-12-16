Prepare Dataset Challenge

#Overview

This is the code for [this](https://youtu.be/0xVqLJe9_CY) video by Siraj on Youtube. The brainscan dataset is entirely fictional, but serves as a good example on how to prepare a dataset. Real examples do exist but, too many features to sift through for a short video. 

##Dependencies

* tensorflow (https://www.tensorflow.org/get_started/os_setup)
* numpy (pip install numpy) 


##Demo

Run the following in terminal
```
$ python softmax.py --train simdata/linear_data_train.csv --test simdata/linear_data_eval.csv --num_epochs 5 --verbose True
Initialized!
```

##Credits

Credits go to [Jason Baldridge](https://github.com/jasonbaldridge). I've merely created a wrapper to get people started.
