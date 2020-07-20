# Deep Learning with Keras

Kares is an API which provides us with a series of functions, that allow us to quickly define our neural network, train it and evaluate it's performance. Keras doesn't actually run the code.

## Model Layers

### Common

#### Dense

The Dense layer is a specified number of neurons, they all connect to all the neurons in the next layer.

#### Dropout

The Dropout layer randomly sets some of the inputs it recieves to 0, this helps to generalise the model and reduce overfitting.

### Shaping Layers

#### Reshape

`Reshape((target_shape), inputs_shape=(input_shape))` This can reduce an input of shape (12, 0) to (3,4)

#### Flattern

`Flattern()` this transforms the tensors into a single dimension vector

#### Permute

Sometimes we want to switch the order of the dimensions, you can do this using `permute((2,1), input_shape=(15,20))` -> (None, 20, 15)

#### RepeatVector

`RepeatVector(n)` will repeat the vector n times

### Merging Layers

Merging layers connects inputs together to produce a merged layer.

#### Add

Adds a list of tensors of the same shape together and returns a tensor of the same shape.

#### Subtract

Subtracts a list of tensors of the same shape together and returns a tensor of the same shape.

#### Multiply

Multiplies a list of tensors of the same shape together and returns a tensor of the same shape.

#### Average and Multiply

I think you know where this is going....

#### Concatenate

....

#### Dot

Gives you a dot product of two vectos along the specified axis.

