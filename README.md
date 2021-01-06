# Sentiment_classifier_fer2013

### description

This is a project developed just for fun and to practice the knowledge acquired in the management of pytorch
with its torchvision package, therefore it will not be as well documented as the rest of my projects

### technologies used

* pythorch
* torchvision
* numpy
* json
* matplotlib
* opencv
* time
* drive
* pandas
* mxnet

### objective

create an emotion classifier using the Fer2013 dataset to train the densenet 121 pre-trained model


### results

train accuracy = 74.03%
valid accuracy = 65.23%

As you can see, the results tell us that the model is a little over-adjusted since by giving us a "high" precision in
training and a lower one in the validation, this does not manage to generalize in new data, but the results when using the model
to predict in images of memes are fun.
