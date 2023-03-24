# Week 6

## Synthesis Questions
### Convolution
- What is the name for the smaller grid that convolves over a larger image?
	- Kernel
- What are some examples of what you can do to images if you convolve them with special matrices?
	- Blur, edge detection and image sharpening
- How does Gaussian blur "work"?
	- Having a kernel with values sample from a Gaussian distribution where the center pixel has the highest weight and the edge pixels have the lowest weight. This way the pixel with be blurred.
- What is the name for the actual operation that occurs when the smaller grid is overlaid on the larger one?
	- Convolution
- Give an example of a 3x3 matrix that would not do anything to the image it convolves over. Why does it not impact the image?
	- A matrix with 1 in the center and eight 0s surrounding it. With that kernel, the pixel will be preserved and surrounding pixels will have no effect on the result since their weight is 0.

### CNN
- The architecture of a CNN is loosely based on what part of the brain?
	- Connectivity pattern of neurons in the human brain and inspired by the organization of the visual cortex.
- What is stride length?
	- The step size of kernels iterating over the image. Default is 1.
- What is padding?
	- Additional 0 pixels added to surround the image.
- Why is padding useful?
	- Useful to control the dimensionality of the convolved feature.
- What is the objective of the convolutional layer in a CNN?
	- To extract features like edges, color, and gradient orientation from images.
- What is the purpose of the pooling layer in a CNN?
	- Decrease the computational power required to process data through dimensionality reduction.
- What are the two ways to pool shown to you in the article?
	- Max pooling and average pooling.
- What is flattening and when is it done in a CNN?
	- Taking a multidimensional matrix and converting it into a column vector. Usually done in the end to feed the output into regular neural networks.
- What is the purpose of the feedforward layer in a CNN?
	- To allow for back propagation and learning based on softmax classification.
- How do the convolutional layers before the feedforward layer in a CNN allow for higher accuracy?
	- Unlike traditional layers, convolutional layers are able to capture the spatial and temporal dependencies in an image, which can be fed into a neural network to train on.
