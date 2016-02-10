# eg_mnist
Trying to find best general-algorithm solution to the MNIST Problem to then expand to bigger ones (maybe one day out of the image-analysis problems).

I used Lasagne Convolutional Neural Network, 
you can run my algorithm using python mnist.py <proportion of data to use>
<proportion of data to use> is optionnal and should vary between 0 and 1, the default value being 1

I achieve an accuracy of 99.54 % on MNIST test set which this algorithm which put me at the 23rd world place according to http://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html. And much higher given most of the better solutions use combinations of algorithms.

However, I should mention that my job was facilitated by the fact that I could use much more powerful GPU on Amazon cloud that most of those brillant researcher didn't have when they published their paper.

Eric Guillaume

