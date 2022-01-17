# Anime-Face-Generator
The project Anime-Face-Generator is a Generative Adversarial Network (GAN) based model which employs two CNN models within itself.
1. Discriminator Model: A simple classification model which classifies the given input, in this case anime face images into two catagories, whether the image is from the data-set or the image it faces is the one generator by generator model.
2. Generator Model: A CNN model which is trained on dataset to produce images similar to the dataset. What makes it interesting is the fact that discriminator model is used a part of loss function for generator model, hence the name adversarial. See, both models discriminator and generator model compete with each other, generator tries to fool the discriminator and discriminator tries to not le generator model do so.
 
