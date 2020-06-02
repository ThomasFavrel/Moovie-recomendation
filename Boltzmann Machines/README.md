# Boltzmann Machine
<img src="https://miro.medium.com/max/864/1*Ere0a83PN-Rj7DF5_IVZdg.png" width="800">

A Boltzmann Machine is a network of symmetrically connected, neuron-like units that make stochastic decisions about whether to be on or off. Boltzmann machines have a simple learning algorithm that allows them to discover interesting features in datasets composed of binary vectors. The learning algorithm is very slow in networks with many layers of feature detectors, but it can be made much faster by learning one layer of feature detectors at a time.

This is my PyTorch implementation of the paper [Restricted Boltzmann Machines for Collaborative Filtering](https://www.cs.toronto.edu/~rsalakhu/papers/rbmcf.pdf) by Ruslan Salakhutdinov, Andriy Mnih, and Geoffrey Hinton (2007). In particular, I trained the RBM model with contrastive divergence on the public Movielens-1M dataset.

<img src="https://github.com/khanhnamle1994/transfer-rec/blob/master/Boltzmann-Machines-Experiments/RBM-CF-PyTorch/pics/Fig1.png" width="800">

<img src="https://qph.fs.quoracdn.net/main-qimg-0f880856d4d1e886bda98ba2b292e6aa.webp" width="800">


document useful for understanding the algorithm : https://christian-igel.github.io/paper/TRBMAI.pdf
