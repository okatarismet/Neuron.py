# Neuron.py
Open Source NeuralNetwork API





# API

#### Model


```sh
model = Model()
```
```sh
model.add(output_shape=16,input_shape=16,activation="relu")
```
```sh
model.build(loss="meanSquare", optimizer="adams", metrics="euclidian")
```
```sh
model.fit(trainX,trainY,epochs=1,learning_rate= 0.1)
```
