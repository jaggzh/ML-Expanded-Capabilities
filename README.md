# ML-Expanded-Capabilities
References for Machine Learning/AI/Neural Nets -- Those which inspire ideas of the expanded potentials of our systems.

## Attention Is All You Need
https://arxiv.org/abs/1706.03762
This method claims to do away with the need for RNNs and CNNs, introducing (or using) methods of "Positional Encoding", and "Multi-Head Attention" (and Masked Multi-Head Attention) mechanisms in their model.

## Video Frame Interpolation via Adaptive Separable Convolution
https://arxiv.org/abs/1708.01692
This model creates interpolated frames between lower frame-rate video input. However, instead of the more usual direct output of the frames, it generates a set of image processing kernels for each pair of inputs -- the kernels operate on the input image pair, producing the final interpolated frame.

## StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation
https://arxiv.org/abs/1711.09020
Currently, usually a GAN handles a single domain. In this model, a Star structure is used to have a single Generator learn mappings across multiple domains. With different datasets, however, different labels are available, for instance, one might include "hair color and gender" but lack facial expressions like 'happy' and 'angry'. To solve this they introduce a mask vector, which allows the model to exploit and incorporate valuable data from different datasets, even without them matching in their labeling.
