# PRODIGY_ML_05

# Food Image Classification with DenseNet201 by Sana Liaqat

**Overview**

This project presents a food image classification system using the DenseNet201 architecture, implemented with Keras and TensorFlow. It aims to classify food items from the Food-101 dataset, which contains 101,000 images categorized into 101 different food classes.

**Key Features**

1. Dataset: Utilizes the Food-101 dataset, consisting of 101,000 images of food items, each labeled with one of 101 distinct categories. The dataset is well-balanced and includes various types of food, making it ideal for training a robust classification model.
2. Model Architecture: Implements DenseNet201, a deep convolutional neural network known for its efficient feature reuse and improved gradient flow. DenseNet201 uses dense blocks to enhance performance and reduce the number of parameters compared to traditional architectures.
3. Transfer Learning: Leverages pre-trained weights from DenseNet201, initially trained on the ImageNet dataset, to improve classification accuracy on the food images. Fine-tuning is performed to adapt the model to the specific task of food classification.
4. Data Augmentation: Applies various augmentation techniques, such as rotation, scaling, and flipping, to artificially expand the training dataset and improve the model's generalization ability.
5. Evaluation: The model's performance is evaluated using metrics such as accuracy and loss on a validation set, ensuring reliable and effective classification.

**Implementation**

1. Preprocessing: Images are resized and normalized to fit the input requirements of DenseNet201. Data augmentation techniques are applied to enhance the robustness of the model.
2. Training: The model is trained using a combination of categorical crossentropy loss and the Adam optimizer. Early stopping is used to prevent overfitting and ensure optimal model performance.
3. Testing: The final model is evaluated on a test set to assess its accuracy and ability to generalize to unseen data.

**Results**

The DenseNet201 model demonstrates strong performance in classifying food images with high accuracy. The use of transfer learning and data augmentation contributes to the model's effectiveness in handling diverse and complex food images.

**Future Work**

Potential future improvements include experimenting with other neural network architectures, incorporating additional data sources, and deploying the model in a real-world application for food recognition.
