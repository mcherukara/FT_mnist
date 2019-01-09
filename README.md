FT_mnist

CNN classifier on the Fourier Transform of MNIST data with >96% accuracy. This increases to >98% accuracy if intensity and phase are fed as two channels (see v3_ft_multi_mnist_test.ipynb)

Also has a traditional CNN classifier with ~99.4% accuracy in mnist_baseline

Background:

Diffraction imaging techniques (optical or X-ray) in the far-field measure the fourier transform of the real-space object. Recovering  the real-space image from this diffraction data is computationally challenging. Consequently, the ability to extract any information from the FT image is extremely valuable.

v4 includes hyper_parameter optimization with hyperas which is a wrapper for hyperopt. Only marginal improvement.
