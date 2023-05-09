# Introduction
In this project it has it has been demonstrated how good Independent Component Analysis performs while removing artifacts from images.
Independent Component Analysis or ICA is a statistical method which is widely used in blind source separation(BSS). It is widely used in retrieving signals but
recently it has been using also in retrieving images from artifacts. It is used in separating individual signals from mixed signals. A simple application of ICA is
'Cocktail Party problem'. With ICA, signals (or data)can be seperated from a linear mixture with other variables or artifacts. These artifacts can be gaussian, non
gaussian, or log-gaussian. 
It is proven that ICA acts well where the signal is mixed with non-gaussian noises. There are two well known algorithms in ICA - Infomax and FastICA. 
Here with this project I have used FastICA to separate noises from Image. 
# Workflow
First, I have uploaded two gray scale images. Then, I have added these images with random matrix (Gaussian, Non-Gaussian, Log-Gaussian). Here matrixes acted as
random noise which can come out from different sources while acquiring images. After mixing images with random matrix FastICA algorithm was run to this mixture
for cancelling the noises and separate images. I have run the iterations for more than thousand times. 
Lastly, the input and output images were displayed including histograms of the images. 
# Result
In three different cases of noises - Gaussian, Non-Gaussian, and Log-Gaussian - it was found that ICA acted well in case of the noise is non-gaussian. 
# Software Packages
Python, Numpy, skearn.decomposition.FastICA, Matplotlib, PIL, Skimage
# Documentaion
ICA: 
https://en.wikipedia.org/wiki/Independent_component_analysis , 
https://www.cs.helsinki.fi/u/ahyvarin/whatisica.shtml;
FastICA: 
https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.FastICA.html
