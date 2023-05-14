# dogs-cats
This project is inspired by the Kaggle Challange held in 2003 in which thousands of images of cats and dogs were given and a model was to be built to classify those images into cats and dogs. The best accuracy achieved in that competition was 98%!

I used a subset of that data and built my model, in the original dataset there were around 25000 images for training but I am only using 2000 images..
I used three different achitectures to train this dataset and increased the validation accuracy from around 73% to 96%!!!

The basic steps follwed in each architecture was:
* Resize the images to desired input size and apply necesaary pre processing like shear,rotate,shift etc.
* Design, train and validate the model using the dataset.
* Download an image from the internet and test it on the trained model.
