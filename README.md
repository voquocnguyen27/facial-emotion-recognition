# Facial-Emotion-Recognition
PBL project about using CNN to recognize human facial emotion
# Dataset
For this project, I'm using FER-2013 to test my model with as much reality as possible.

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 3,589 examples.

You can download all the data used in this project by following these API command:
```bash
kaggle datasets download -d voquocnguyen/facial
```
# Environment
For this project, I chose Kaggle as the base environment because of the support for GPU training, especially for image classification like this project.
# Coding
All my code is available on Github, and the result can be regenerated due to the static random variables.
# References
Pham Luan, The Huynh Vu, and Tuan Anh Tran. "Facial Expression Recognition using Residual Masking Network". In: Proc. ICPR. 2020.
