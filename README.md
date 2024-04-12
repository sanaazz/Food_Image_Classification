# Image Classification Project

## Project Overview
This project focuses on developing image classification models using transfer learning with various pre-trained architectures. The goal is to accurately classify images from a dataset into 22 distinct classes. Given the challenges of incorrect labels within the dataset, advanced techniques such as data augmentation and regularization were employed to enhance model robustness and performance.

## Models Used and Final Model Selection
- **InceptionResNetV2**: Utilized for its deep architecture combining Inception modules with residual connections. Selected as the final model due to its superior accuracy and lower loss compared to other models, demonstrating robust generalization and effective learning even in the presence of noisy data.
- **NASNetMobile**: Chosen for its efficiency, making it suitable for applications where model size and speed are critical. While highly efficient, it was slightly less accurate in this specific application.
- **InceptionV3**: Known for its efficiency and effectiveness, but in this project, it did not outperform InceptionResNetV2 in terms of accuracy and loss.

### Why InceptionResNetV2 as the Final Model
The InceptionResNetV2 model provided the highest accuracy and the lowest loss rates during testing phases, indicating a better handling of the complex patterns in the dataset and a stronger resistance to overfitting compared to NASNetMobile and InceptionV3. Its deep architecture, which combines the benefits of Inception modules for handling different scales of image details and residual connections for preventing gradient vanishing, makes it particularly effective for challenging datasets like ours with potential label inaccuracies.

