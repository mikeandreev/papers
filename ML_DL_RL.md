# Numerical AI
ML, DL, RL and other numerical  approaches to solving AI related  

## Activation functions

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

# Свалочка
## Cache L1

* Rupesh Kumar Srivastava, Klaus Greff,  and Jürgen Schmidhuber.
Highway networks
arXiv preprint arXiv:1505.00387, 2015.

* Barret Zoph, Vijay Vasudevan, Jonathon Shlens, and Quoc V Le. 
Learning transferable architectures for scalable image recognition. 
arXiv preprint arXiv:1707.07012, 2017.

* https://arxiv.org/abs/1803.09820
A disciplined approach to neural network hyper-parameters: Part 1 -- learning rate, batch size, momentum, and weight decay
Leslie N. Smith
Apr 2018

## Cache L2

### Texture recognition
https://arxiv.org/abs/1411.6836
https://www.robots.ox.ac.uk/~vgg/publications/2015/Cimpoi15a/cimpoi15a.pdf
https://people.eecs.berkeley.edu/~malik/papers/renningermalik.pdf
http://haralick.org/journals/TexturalFeatures.pdf

https://github.com/mcimpoi/deep-fbanks


http://vision.ucla.edu/~doretto/publications/saisanDWS01cvpr.pdf
http://cat.cvc.uab.es/~joost/papers/caip2013.pdf



https://arxiv.org/abs/1507.02620
https://www.robots.ox.ac.uk/~vgg/publications/2015/Cimpoi15/cimpoi15.pdf

