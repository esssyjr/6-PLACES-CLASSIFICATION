# Image Classification Model

This repository contains a deep learning model for classifying images into categories such as 'buildings', 'forest', 'glacier', 'mountain', 'sea', and 'street'. The model, built using MobileNet transfer learning, achieved an 81% training accuracy and 78% validation accuracy.

## Computer Vision Work

### Table of Contents

1. [Dataset](#dataset)
2. [Model Architecture](#model-architecture)
3. [Results](#results)
4. [Future Work](#future-work)
5. [Contributing](#contributing)
6. [Citation](#citation)

### Dataset

The training dataset consists of a balanced collection of 11,230 images for each class: 'buildings', 'forest', 'glacier', 'mountain', 'sea', and 'street'. A validation set of 598 images and a test set of 7,301 images are also part of the dataset. The data is split into training and validation sets to evaluate the model's performance.

### Data Augmentation

I used an image data generator to augment the data, providing more photos to improve the model's robustness.

### Model Architecture

The classification model is built on top of the MobileNet architecture, a lightweight and efficient convolutional neural network (CNN) suitable for mobile and embedded vision applications. I excluded the top layer and added my own. I used fine-tuning techniques to achieve better accuracy. The use of different transfer learning models was explored.

### Results

The model achieved an impressive 81% accuracy on the training set and 78% accuracy on the validation set.

### Future Work

While the current model performs well, there is room for improvement. Future work could focus on:

- **Fine-tuning:** Further refine the model by adjusting hyperparameters or exploring different architectures.
  
- **Data Expansion:** Increase the dataset size with additional diverse images to enhance the model's generalization capability.

- **Regularization Techniques:** Implement regularization methods to prevent overfitting and improve model performance on unseen data.

- **Exploration of Other Techniques:** Investigate and implement other state-of-the-art techniques in computer vision for potential performance gains.

Contributors are encouraged to explore these avenues and contribute to the ongoing development of the model.

### Contribution

Contributions are welcome! If you find any issues or have suggestions, feel free to open an issue or submit a pull request.

### Citation

[Dataset Source](https://www.kaggle.com/datasets/puneet6060/intel-image-classification/data) - Kaggle Intel Image Classification Data
