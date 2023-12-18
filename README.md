# Cat and Dog Image Classifier
## Description
Classify cat and dog images using TensorFlow 2.0 and Keras. Achieve at least 63% accuracy, with extra credit for 70%.

## Instructions
Cell 3: Set variables for image generators. Use ImageDataGenerator for train, validation, and test sets. Rescale tensors from 0-255 to 0-1. For test_data_gen, set shuffle=False.

Cell 4: Plot five random training images using the plotImages function.

Cell 5: Recreate train_image_generator with 4-6 random transformations to prevent overfitting.

Cell 7: Create a Sequential model with Conv2D, MaxPooling2D layers, and a fully connected layer activated by ReLU. Compile with specified optimizer, loss, and metrics.

Cell 8: Use the fit method to train the network. Set arguments for x, steps_per_epoch, epochs, validation_data, and validation_steps.

Cell 9: Visualize the accuracy and loss of the model.

Cell 10: Use the model to predict if test images are cats or dogs. Visualize with the plotImages function.

Cell 11: Run the final cell to check if the challenge is passed.

## Solution Link
https://colab.research.google.com/github/freeCodeCamp/boilerplate-cat-and-dog-image-classifier/blob/master/fcc_cat_dog.ipynb#scrollTo=4IH86Ux_u7TZ&uniqifier=1
