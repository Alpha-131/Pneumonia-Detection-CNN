# Pneumonia-Detection-CNN
# **Pneumonia Detection with Transfer Learning**

Detecting pneumonia in pediatric chest X-ray images using VGG16 and ResNet152V2 pre-trained models and comparing them. Dataset includes 5,863 images categorized into Pneumonia and Normal.

## Models
### VGG16
- Simple and effective CNN with 16 weight layers.
- Excels at capturing intricate patterns.
- Straightforward design for easy implementation.
- Suitable for pneumonia detection by extracting relevant features from chest X-ray images.

### ResNet152V2
- Utilizes a residual learning framework to address the vanishing gradient problem.
- Specifically, ResNet152V2 is based on a deep architecture with 152 layers.
- The model employs residual blocks, allowing it to learn residual functions to enhance training.
- Pre-trained on ImageNet, providing a solid foundation for various computer vision tasks.
- Transfer learning is facilitated by freezing the pre-trained layers and adding a custom head for specific tasks.


## Implementation
Code uses TensorFlow and Keras for training and fine-tuning. Evaluation metrics include accuracy, precision, recall, and F1-score.


# Model Performance Summary

## VGG16 Model:
**Overall Inference:** The VGG16 model demonstrates strong performance, particularly in correctly identifying positive cases (pneumonia). It achieves high precision and recall for the positive class.

## ResNet152V2 Model:
**Overall Inference:** The ResNet152V2 model excels in correctly identifying positive cases (pneumonia) with impressive precision and recall. However, it exhibits a lower recall for the negative class compared to VGG16.

## General Observations:
- Both models showcase comparable accuracy, with VGG16 slightly outperforming ResNet152V2.
- The choice between the two models may depend on specific requirements and the importance of precision or recall for the given task.

These insights provide a concise summary of the strengths and areas for improvement for each model, assisting in informed decision-making.

## Conclusion
Comparing model performance to guide further research in pneumonia detection.
