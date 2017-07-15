# Kaggle-InstaCart
This is some (messy) code I used for my submission to the InstaCart Kaggle competition.  

This includes, most importantly, the data processing in pandas of the data set.  The data set was somewhat sizeable, so efficiently using vectorization, and built-in groupby functions was key to creating performant data processing.  

I have two notebooks here, one applies a fully-connected, feed-forward neural network to the data, ("Keras_NN").  The other applies a gradient boosted tree (specifically LightGBM) to the data.  Both get similar results in this case.  

Please raise an issue if you find any bugs or have any comments.
