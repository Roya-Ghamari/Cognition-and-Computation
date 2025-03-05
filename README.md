This project implements and analyzes Deep Belief Networks (DBNs) for classifying the Fashion-MNIST dataset. The project compares the performance of DBNs with a Feedforward Neural Network (FFNN).


* Models

Deep Belief Network (DBN) with RBMs.

Feedforward Neural Network (FFNN) as a baseline.


* Techniques Used 

Pre-training RBMs using Contrastive Divergence.

Fine-tuning with supervised learning.

Linear Readout Layers for classification.

Model Robustness Analysis using Gaussian noise.

Adversarial Attacks (Fast Gradient Sign Method) to test model vulnerability.

Visualization of learned weights, hidden representations, confusion matrices, and hierarchical clustering.


* Key Findings 

DBNs achieved higher accuracy compared to the FFNN, particularly in handling noisy data.

Robustness tests revealed DBNs outperform FFNNs when subjected to increasing noise levels.

Adversarial attacks demonstrated DBNs' susceptibility to perturbations, highlighting areas for improvement.
