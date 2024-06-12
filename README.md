# Overview
This repository presents "Neural Networks for People Who Get Confused Easily." It is not intended as a comprehensive tutorial on neural networks but rather as a detailed set of notes to augment those using other resources to learn about basic feedforward networks.

# Who Gets Confused Easily?
I do! Here, confusion relates to the details of matrix multiplication—whether to left or right multiply, which matrices are transposed, the sizes of matrices as they progress through the network, how broadcasting works, and so on.

# Contributions
1. **Diagrams**: The main contribution is a series of diagrams in PDF form. These are extremely large (e.g., 20 x 20 inches) and attempt to present both an overview and, if you zoom in, a very detailed breakdown of the math involved. I haven't seen anyone else present these topics quite this way. They attempt, for example, to merge the input vector approach usually seen in beginner examples with the more common mini-batch method of an input matrix.
2. **Detailed Derivations**: Included is a more detailed derivation of He initialization than is typically presented, as well as a derivation of the softmax derivative.
3. **Flexible Code**: Unlike many beginner examples which hard code the size of networks, this repository uses Python classes that allow you to flexibly define the size of a network for a given problem. This approach is closer to libraries like PyTorch (though obviously, MUCH more simplified).

# Updates Needed
1. **Future Additions**: I hope to add both momentum and Adam to the feedforward network code.
2. **Diagram Updates**: Diagrams of the forward and backward pass are about 80% complete and should be added later this month.
3. **Error Corrections**: Inevitably, there are a few errors hidden in the documents and code. I will attempt to update the materials as I become aware of them.
