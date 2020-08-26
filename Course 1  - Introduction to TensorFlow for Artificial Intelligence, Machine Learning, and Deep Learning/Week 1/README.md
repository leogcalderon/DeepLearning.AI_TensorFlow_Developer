
## A new programming paradigm
We put answers and data to models and Machine Learning give us the rules.

## The 'Hello world' of neural networks
Single neuron with a only one input value.

```python
model = keras.Sequential([keras.layers.Dense(units = 1, input_shape=[1])])
model.compile(optimizer = 'sgd', loss = 'mean_squared_error')
model.fit(x, y, epochs = 500)
print(model.predict([ ... ])
```


