#Numerical AI
ML, DL, RL and other numerical  approaches to solving AI related  

##Activation functions

*  Swish:  f(x) = x * sigmoid(x)    
[Swish: a Self-Gated Activation Function](https://arxiv.org/abs/1710.05941v1) -- Prajit Ramachandran, Barret Zoph, Quoc V. Le
Oct 2017

* ELU. The exponential linear activation: 
x if x > 0 
alpha * (exp(x)-1) if x < 0
Fast and Accurate Deep Network Learning by Exponential Linear Units (ELUs)](https://arxiv.org/abs/1511.07289) -- Djork-Arné Clevert, Thomas Unterthiner, Sepp Hochreiter
Feb 2016

* Scaled Exponential Linear Unit (SELU)
scale * x if x > 0 
scale * alpha * (exp(x) - 1) if x < 0
[TF Keras docs](https://www.tensorflow.org/api_docs/python/tf/keras/activations/selu)
[Self-Normalizing Neural Networks](https://arxiv.org/abs/1706.02515)  -- Günter Klambauer, Thomas Unterthiner, Andreas Mayr, Sepp Hochreiter
Sep 2017
 Initialization : https://www.tensorflow.org/api_docs/python/tf/keras/initializers/lecun_normal 
