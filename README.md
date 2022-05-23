# Flowers-Recognition
This project uses a Convolutional Neural Network (CNN) to predict flowers of 5 types using flower recogniton dataset on Kaggle.

There are 5 types of flowers that are predicted and trained on:

- Daisy
- Dandelion
- Rose
- Sunflower
- Tulip
There are 4242 images in the original dataset.

I have trained Convolutional Neural Network written in Keras to predict the type of flower on the testing set. Also used ImageDataGenerator to augment the training set and avoid overfitting problem.

All the photos in the dataset were resized to (224,224) and normalization was applied to each pixel in the image, resulting in an image that is in the shape of 224×224×3, with each pixel value ranging from [0, 1]. 

Image Data Augmentation is responsible for applying a variety of transformational procedures to each image in the dataset to increase the dataset's size appropriately. Cropping, rotating, vertically flipping, and scaling the photographs were used as a result of our data augmentation approaches.

Finally the accuracy on the testing set is 85%.

Link to the data: https://www.kaggle.com/alxmamaev/flowers-recognition
