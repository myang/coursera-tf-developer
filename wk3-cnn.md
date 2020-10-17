* the ultimate concept of convolution is that they narrow down the content of the image to focus on specific, distinct, details.
* [pooling](https://www.kaggle.com/questions-and-answers/59502) is to down sampling of an image
* add one convolution layer and one pooling layer:

|conv num|epoch time|accuracy(train/test)|     
|--------|----------|--------------------|     
|   16   |    17s   |    99.49/98.40     |     
|   32   |    25s   |    99.53/98.48     |     
|   64   |    39s   |    99.62/98.43     |

* add two convolution and two pooling layers:

|conv num|epoch time|accuracy(train/test)|     
|--------|----------|--------------------|     
|   16   |    18s   |    99.24/98.86     |     
|   32   |    33s   |    99.36/98.98     |     
