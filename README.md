## Content

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal).

There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

You can find the dataset here: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

## Model

I have used transfer learning using the following models:

MobileNet(86.22)

VGG16(85.26)

DenseNet201(82.53)

Xception(82.05)

DenseNet121(77.56)

InceptionV3(76.60)

<img src='/Images/TrainedModels.png'>

As seen above MobileNet gives the highest accuracy of 86.22 after epoch 1 so the best model is MobileNet

## Output

Here is the output image:

<img src='/Images/output.png'>
