# VISIOPE_project
This repository is specifically designed for the classification, using colab, of the CIFAR-10 dataset available on Kaggle at https://www.kaggle.com/c/cifar-10/
By providing kaggle.json it connects to the Kaggle account then it downloads and extracts the dataset followed by upsampling.
After upsampling we convert images to jpg format and save them to the upsampled_images folder with the new name having a label as their initials.
Labels were assigned for classification meanwhile upsampled images are then converted to arrays and all arrays were pilled up to get them ready for input to architecture.
We split data for test and train due to system limitations.
Before inputing data to architecture we normalized it.
Used MobileNet v2 architecture due to its lightweight ness.
Then we get the pre-trained model weights perform transfer learning
After training for 5 epochs I got 73.75% accuracy on test dat
There is a section named as Predictive System. It can be used to predict images uploaded only with jpg file
