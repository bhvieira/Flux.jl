## Basic Layers

These core layers form the foundation of almost all neural networks.

```@docs
Chain
Dense
```

## Convolution and Pooling Layers

These layers are used to build convolutional neural networks (CNNs).

```@docs
Conv
MaxPool
MeanPool
DepthwiseConv
ConvTranspose
CrossCor
```

## Recurrent Layers

Much like the core layers above, but can be used to process sequence data (as well as other kinds of structured data).

```@docs
RNN
LSTM
GRU
Flux.Recur
```

## Other General Purpose Layers
These are marginally more obscure than the Basic Layers.
But in contrast to the layers described in the other sections are not readily grouped around a particular purpose (e.g. CNNs or RNNs).

```@docs
Maxout
SkipConnection
```


## Normalisation & Regularisation

These layers don't affect the structure of the network but may improve training times or reduce overfitting.

```@docs
BatchNorm
Dropout
Flux.dropout
AlphaDropout
LayerNorm
GroupNorm
```

## Cost Functions
```@docs
Flux.mse
Flux.crossentropy
Flux.logitcrossentropy
Flux.binarycrossentropy
Flux.logitbinarycrossentropy
Flux.kldivergence
Flux.poisson
Flux.hinge
```
