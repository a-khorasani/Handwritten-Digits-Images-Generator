# Handwritten-Digits-Images-Generator
handwritten digits images producer is a project that i've started recently and I used MNIST dataset that includs 60,000 images of handwritten digits images for my model. I implemented this project by pytorch and Conditional Generative Adversarial Network (cGAN) to train my model to produce a image of any number you choose!
This was very informative for me, I hope it will be useful for you too!!!

A conditional generative adversarial network (CGAN) is a type of GAN model where a condition is put in place to get the output.
(GAN) is a deep learning framework that is used to generate random, plausible examples based on our needs. It contains two essential parts that are always competing against each other in a repetitive process (as adversaries). These two essential parts are:

_Generator Network: It is the neural network responsible for creating (or generating) new data. They can be in the form of an image, text, video, sound, etc., as per the data they are trained on.
_Discriminator Network: It’s work is to distinguish between real and fake data from the dataset and data generated by the generator.
The responsibility or objective of the generator model is to create new data real enough to “fool” the discriminator so that it cannot distinguish between real and fake (generated) data, whereas the role of the discriminator is to be able to identify if the data is generated or real data.
