# ResNet-AppleLeaf-Disease-Detection

This repository contains a **ResNet50** deep learning model for detecting apple leaf diseases. It classifies leaves into **Healthy, Rust, Scab, or Multiple Diseases** using residual learning.

![image](https://github.com/user-attachments/assets/fc648d8a-9d7e-426c-8205-b70d4d737345)![image](https://github.com/user-attachments/assets/5c8525cb-057d-4a16-af33-b9becdda3045)![image](https://github.com/user-attachments/assets/7373b489-1ca5-434c-b42b-bafe6d691db1)![image](https://github.com/user-attachments/assets/2fa3d99d-28da-4e52-b16c-b0571ecd1bdb)

## Dataset
- Dataset: [Plant Pathology 2020 - FGVC7 | Kaggle](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7)
- Includes apple leaf images.

## Model Overview
- **ResNet50 architecture** with **skip connections** to solve the vanishing gradient problem.
- Uses **pre-trained ImageNet weights** for transfer learning.
- **Global Average Pooling (GAP)** to reduce overfitting.
- Final classification through a **Softmax layer**.

## Installation & Requirements
To run this project, install dependencies:
```bash
pip install tensorflow keras numpy pandas matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ResNet50-AppleLeaf-Disease-Detection.git
   cd ResNet50-AppleLeaf-Disease-Detection
   ```
2. Open and run `resnet50_model.ipynb` in Jupyter Notebook or Google Colab.
3. Load the dataset and train the model.

## Results
- Achieved **90% accuracy** on test data.
- Performs well but slightly behind **DenseNet121** and **InceptionV3**.

## Future Improvements
- Fine-tuning on a larger dataset.
- Applying **data augmentation** to enhance generalization.

## License
This project is licensed under the **MIT License**.
