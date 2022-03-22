# ML4Code

Resources about Machine Learning for Code Analysis.

## PAPERS

### Code Embedding

* [code2vec: Learning Distributed Representations of Code](./paper/code2vec-popl19.pdf)
  - [DEMO](https://code2vec.org/)
* [Flow2Vec: Value-Flow-Based Precise Code Embedding](./paper/oopsla20.pdf)

### For Code Clone

* [Code Clones: Detection and Management](./paper/1-s2.0-S1877050918308123-main.pdf)
* [A Survey of Software Clone Detection From Security Perspective](./paper/A_Survey_of_Software_Clone_Detection_From_Security_Perspective.pdf)

## LIBRARIES (for Golang)

### Algorithms
* [GoLearn](https://github.com/sjwhitworth/golearn)

GoLearn is one of the most popular libraries in the Go language. It is also known as the ‘batteries included’ machine learning library for Go. It aims to contribute simplicity paired with customizability. Some of its features are-

The library includes helper functions for data like cross-validation, train splitting as well as test splitting.
It is similar to the popular Scikit-learn library in Python as it implements the Scikit-learn interface of Fit/Predict.
This library comes with practical examples.
Know more here.

* [Gorgonia](https://github.com/gorgonia/gorgonia)

Gorgonia helps in facilitating machine learning entirely in Go. The primary goal of this library is to be a highly performant machine learning as well as graph computation-based library that can scale across multiple machines. It also contributes a platform for the exploration of non-standard deep-learning as well as neural network-related research. It can perform processes like neo-Hebbian learning, corner-cutting algorithms, among others. Some of its features are-

Gorgonia can perform automatic differentiation, symbolic differentiation, gradient descent optimisations and numerical stabilisation.
The library provides many convenience functions to help create neural networks.
It supports CUDA and GPGPU computation.
Know more here.

* [goml](https://github.com/cdipaolo/goml)

goml is a machine learning library written entirely in Go language which allows developers to include machine learning into their applications. The library consists of various models which help in learning in an online as well as the reactive manner by passing data to streams held on channels. Some of the features of this library include-

### AST