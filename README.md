# Stroke Classification from CT scans using CNNs
This project focuses on building a deep learning model to classify grayscale medical images into three categories: Bleeding, Ischemia, and Healthy. The primary aim is to leverage state-of-the-art CNN architectures such as ResNet, EfficientNet and DensNet, while taking into account class imbalance and the special characteristics of grayscale image data.

## 🔍 Problem Description
Medical image classification is a crucial task in the context of CT scans, especially when used to detect acute conditions. CT images are grayscale and often complex, with subtle differences between pathological and normal tissues. These images can be noisy, suffer from intra-class variability, and frequently exhibit class imbalance — where healthy cases may outnumber pathological ones, or vice versa depending on the dataset. In this project, the goal is to develop a deep learning model capable of automatically classifying CT scan slices into one of the following categories:
- **Bleeding**: Indicators of internal hemorrhage.
- **Ischemia**: Signs of restricted blood flow or infarction.
- **Healthy**: Normal anatomical structure with no evidence of acute pathology.

## 🛠️ Model Architecture
Three convolutional neural network (CNN) architectures are explored in this project:
- **ResNet-18**
- **DenseNet-121**
- **EfficientNet-B0** 
