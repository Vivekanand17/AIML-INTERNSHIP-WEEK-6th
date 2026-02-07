Q: Why does loss decrease initially?
A: Because in the beginning, gradient descent learns the most important and simple patterns first, which quickly reduces the overall error.

Q: Why does validation loss behave differently?
A: Because after some point the model begins memorizing noise or unnecessary details from the training data, which does not work well on unseen data, so validation loss starts increasing.

Q: What happens if model size is doubled?
A: The model becomes more powerful and can learn more complex patterns. This may improve results