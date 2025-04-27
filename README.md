# InceptionV3 Fruit Image Classifier

This project uses a custom dataset of 10 fruits to build an image classifier using the InceptionV3 model. The dataset is collected from Google Images and includes the following classes:

- **Apple**: 451 images
- **Banana**: 391 images
- **Blueberry**: 381 images
- **Cherry**: 401 images
- **Grapes**: 375 images
- **Kiwi**: 408 images
- **Mango**: 437 images
- **Orange**: 403 images
- **Strawberry**: 357 images
- **Watermelon**: 417 images

## Dataset Details
- **Data Augmentation**: Applied (rotation, width/height shift, shear, zoom, horizontal flip)
- **Data Split**: 70% training, 15% validation, 15% testing
- **Model**: InceptionV3 pre-trained on ImageNet with custom layers for classification
- **Accuracy**: 92% test accuracy

## Results
- **Training & Validation Loss**: ![Training & Validation Loss](screenshots/train_val_loss.png)
- **Confusion Matrix**: ![Confusion Matrix](screenshots/confusion_matrix.png)
- **ROC Curve**: ![ROC Curve](screenshots/roc_curve.png)

## Model Deployment
- Deployed in a Flutter app using TensorFlow Lite.

## Files
- [Google Drive Link for .h5 model and dataset](your-link-here)

## Setup and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Ahad-MUST/InceptionV3---Fruit-Image-Classifier-Using-a-Random-Dataset.git
