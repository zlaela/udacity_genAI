# Pytorch

https://pytorch.org/

An open-source ML framework used for developing and training deep learning models. SUports GPU acceleration and dynamic computation graphs.

## Tensors

- `Tensor` - Generalized versions of n-dimensional vectors and matrices. They hold data for processsing with operations like addition or multiplication.
  - Matrices are a 2-dimensional form of tensors
- `Matrix Operations` - Calculations involving matrices (2d arrays)
- `Scalar Values` - Single numbers or quantities that can only have magnitude, not direction (ex: 7, or 3.14).
- `Linear Algebra` - An area of math focusted on vector spaces and oeprations that can be performed on vectors and matrices.

## Loss Functions

- `Loss Function` - Measures how well a model is perfomring by calculating the difference between the prediction and actual result.
- `Cross entropy loss` - A measure used when a model needs to choose between categories (i.e. cat or dog). Shows how well the prediction aligns with the actual category.
  - A lower value means the predictions are closer to the actual.
- `Mean squared error` - The average of the squares of the differences between predicted numbers and actual numbers. Often used for predicting continuous values rather than categories.

## Optimizers

- `Gradients` - Directions and amounts by which a function increases the most. Can be changed in a direction *opposite* to the gradient of the loss function to reduce the loss.
- `Learning rate` - A hyperparameter that specifies the magniutde of the steps when adjusting the neural network's settings during training.
- `Momentum` - A technique that helps accelerate the optimizer in the correct direction and dampens oscillations.
- 

### Useful links

- Introduction to PyTorch Tensors [tutorial] (https://docs.pytorch.org/tutorials/beginner/introyt/tensors_deeper_tutorial.html) has a nice video intro.
- The [docs] (https://docs.pytorch.org/docs/stable/tensors.html), of course.
- CrossEntropyLoss [documentation] (https://pytorch.org/docs/stable/generated/torch.nn.CrossEntropyLoss.html#torch.nn.CrossEntropyLoss).
- MSELoss [documentation] (https://pytorch.org/docs/stable/generated/torch.nn.MSELoss.html#torch.nn.MSELoss).
- Index of Pytorch [loss functions](https://pytorch.org/docs/stable/nn.html#loss-functions).