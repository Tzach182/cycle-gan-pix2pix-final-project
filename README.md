# Computer Vision Using Deep Learning

![alt text](output_gif.gif "Logo Title Text 1")

The left image is real and the rifht image is computer generated.

## Overview

This project utilizes a Cycle-GAN (Generative Adversarial Network) to transform images from a state of without sunglasses to a state of with sunglasses.
The Cycle-GAN framework consists of two generator networks and two discriminator networks, which work in tandem to learn the mapping between the two domains.
The Cycle-GAN is capable of generating realistic and high-quality images with sunglasses based on the input images without sunglasses.
This project was made during my university class: Computer Vision Using Deep Learning.

### Tools used

- Python 
- Pytorch
- NumPy
- OpenCV
- Jupyter Notebook

This project was taken from a Kaggle notebook on this [link](https://www.kaggle.com/code/songseungwon/cyclegan-tutorial-from-scratch-monet-to-photo)
The notebook itself can be found in this repository.
On this repository you can find:
- The original notebook
- A cleaner version of the original notebook with training information.
- A live inference notebook.
- A video of the generated model images side by side the original images.
- A zip of the database used.
- A directory holding the saved model states.

The model was trained on a total of 6,731 images of both states (with sunglasses, without sunglasses).
The model was trained on approx. 150 epochs, trained on Google Colab.
