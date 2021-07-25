# Face Generation
In this project, you'll use generative adversarial networks to generate new images of faces. You will define and train a DCGAN on a dataset of faces. Your goal is to get a generator network to generate new images of faces that look as realistic as possible!

The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the project, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.

## Instructions
To finish the project, you need to install the following dependencies:
- [Numpy](https://numpy.org/)
- [Pytorch](https://pytorch.org/)
- [Matplotlib](https://matplotlib.org/)
  
The ```problem_unittests.py``` file is used as unit tests for the code to complete the project.

## Dataset
You'll be using the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train your adversarial networks. 

Since the project's main focus is on building the GANs, some of the pre-processing have been done for you. Each of the CelebA images has been cropped to remove parts of the image that don't include a face, then resized down to 64x64x3 NumPy images. This pre-processed dataset is a smaller subset of the very large CelebA data, and you can download it by clicking [here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip).

