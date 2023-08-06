We manually used different types of data (image) augmentation techniques to produce diverese and expansive extensions of the provided dataset for better training and more precision of the model.

However, we did not know how to produce labels for the augmented images manually so we could not use the augmented dataset for training.

Then we found Roboflow and uploaded our original dataset there. While creating a new version of the dataset, different pre-processing and data augmentation techniques could automatically be applied with labels. We then used used an API of our Roboflow project to download that new version of our dataset onto our Google Colab notebook and then train it using YOLOv8. This trained model was then deployed to our Roboflow project. Our model can now be used in the form of an API (provided in another .txt file).
