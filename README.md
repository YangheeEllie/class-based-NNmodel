# class-based-NNmodel
some notes for studying class in python and convert my NN-model code into classed based one.
this notes are based on the model 'bayesian SegNet for brain extraction', so some parts from workflow can be different depending on the cases.

### List of elements for NNmodel
#### 1. setting variables:
- input, target, output
- phase train, learning rate, optimizer
- loss, accuracy

#### 2. building objects from tensorflow:
- tf.saver
- tf.summary(or just use dictionary from python)

#### 3. define methods depending on workflow of model
(1) save and  restore model using ckpt
(2) do data arragement/ augmentation (make a dictionary of shuffled 2D images)
(3) set criteria for early stopping 
(4) train the model
(5) test the model

More informations are in 'class_NNmodel'
