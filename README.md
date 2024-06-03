# Satellite-Image-Classification
<br>
In the context of satellite image classification, the dataset was loaded from a mounted drive and organized into training and testing sets, with class-separated directories under specified root directories. Data augmentation, including random rotations, shearing, zooming, shifting, and flips, was applied to the training data using ImageDataGenerator objects, while testing data remained unaltered. Various deep learning models, including CNN, ResNet34, VGG16, and InceptionV3, were trained and evaluated on the dataset with predefined hyperparameters such as epochs, batch size, and learning rate. CNN and InceptionV3 emerged as the top-performing models, outperforming ResNet34 and VGG16. Consequently, these two models were deemed the most suitable for the satellite image classification task.
<br>
DATASET
<br>
https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification
