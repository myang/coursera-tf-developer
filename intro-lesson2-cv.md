* dataset: fashion mnist. Keras has it predefined and refered by a constant.
* python: return two values, each of a tuple.
* Model: 
  * rule1: 
  >>shape of layer 1 shall match shape of data;
  * rule2: 
  >>number of neurons of last layer shall match number of classes you are classifying for.
* use callbacks (array) to end epoch when certain accuracy or loss reaches certain level.
* model.flatten() e.g. 12x12 image results in one-dimensional array which has 144 elements.
* use callback on_epoch_end method to stop trainning when certain loss or accuracy is reached.
