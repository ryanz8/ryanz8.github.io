---
title: "Permutation-Invariant Representation of Neural Networks with Neuron Embeddings"
excerpt: "This project develops an implicit way of representing neural networks to facilitate transplanting of neurons between models. <br/> <img src='/images/neuron_embedding_overview.png'>"
collection: projects
---

Neural networks are traditionally represented in terms of their weights. A key property of this representation is that there are multiple representations of a network which can be obtained by permuting the order of the neurons. These representations are generally not compatible between networks, making recombination a challenge for two arbitrary neural networks - an issue known as the "permutation problem" in neuroevolution. This paper proposes an indirect encoding in which a neural network is represented in terms of interactions between neurons rather than explicit weights, and which works for both fully connected and convolutional networks. In addition to reducing the number of free parameters, this encoding is agnostic to the ordering of neurons, bypassing a key problem for direct weight-based representation. This allows us to transplant individual neurons and layers into another network without accounting for the specific ordering of neurons. We show through experiments on the MNIST and CIFAR-10 datasets that this method is capable of representing networks which achieve comparable performance to direct weight representation, and that combining networks this way preserves a larger degree of performance than through direct weight transfer.

You can download the paper [here](/files/NeuronEmbedding.pdf).

Blog post coming soon.