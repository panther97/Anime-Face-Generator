# Anime-Face-Generator
The project Anime-Face-Generator is a Generative Adversarial Network (GAN) based model which employs two CNN models within itself.
1. Discriminator Model: A simple classification model which classifies the given input, in this case anime face images into two catagories, whether the image is from the data-set or the image it faces is the one generator by generator model.
2. Generator Model: A CNN model which is trained on dataset to produce images similar to the dataset. What makes it interesting is the fact that discriminator model is used a part of loss function for generator model, hence the name adversarial. See, both models discriminator and generator model compete with each other, generator tries to fool the discriminator and discriminator tries to not le generator model do so.
 
Dataset Used : https://www.kaggle.com/splcher/animefacedataset

Original image from dataset:
![Dataset](https://user-images.githubusercontent.com/22273562/149710207-98bc4413-97e1-4512-b53a-b4fd88fdfba0.PNG)

Raw data given to generator model to generate an anime face:

![latent](https://user-images.githubusercontent.com/22273562/149710254-746ee68a-3296-40a7-b4a9-38b7f1c58e01.PNG)

Generated images of anime faces:![generated-images-0025](https://user-images.githubusercontent.com/22273562/149710280-44d8b020-f1f3-46cb-859e-974150f605b3.png)
