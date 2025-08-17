# Brain Tumor Detection Using Deep Learning on MRI Images

## Overview
This project leverages deep learning and computer vision techniques to detect brain tumors from MRI images. It aims to assist radiologists and medical professionals in identifying the presence of tumors with high accuracy, using automated image analysis.

## Features
- Classification of MRI images into tumor and non-tumor categories
- Preprocessing of medical images for enhanced model performance
- State-of-the-art neural network architectures (CNNs)
- Visualization of predictions and model confidence
- Evaluation metrics including accuracy, sensitivity, and specificity

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bhavesh2327/brain-tumor-detection-using-cv.git
   cd brain-tumor-detection-using-cv
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset**
   - The dataset used is publicly available (such as Kaggle's Brain MRI Images for Brain Tumor Detection).
   - Download and extract the dataset into the `data/` directory.

## Usage

1. **Train the model**
   ```bash
   python train.py --data_dir data/
   ```

2. **Test the model**
   ```bash
   python test.py --model_path models/best_model.pth --data_dir data/test/
   ```

3. **Visualize results**
   - Run visualization scripts to see sample predictions on MRI images.

## Dataset Information

- Source: [Kaggle Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)
- Contains labeled images for tumor and normal cases
- Images are preprocessed (normalized, resized) before model training

## Results

- **Accuracy:** Achieved over 95% accuracy on the validation set
- **Sample predictions:** [Include sample images and prediction examples]
- **Model performance:** High sensitivity and specificity for tumor detection


## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements, new features, or bug fixes.

## License

This project is licensed under the MIT License.

---

**Note:** This software is for research and educational purposes only. It should not be used as a substitute for professional medical diagnosis.
