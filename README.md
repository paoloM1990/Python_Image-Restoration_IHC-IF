# Python_Image-Restoration_IHC-IF

In this Jupyter notebook, we use two methods of the Scikit-Image Library in Python for improving the quality of fluorescent images of Immunohistochemistry.

In the first example, we use a "non-local means algorithm" from Scikit-image for reducing the noise of our image of interest. This algorithm replaces the value of a pixel with an average of a selection of other pixels values.

In a second example, we deconvolve our noisy image using "unsupervised Wiener algorithms" from Scikit-image in Python. 
