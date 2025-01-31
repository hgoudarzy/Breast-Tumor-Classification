# Breast Tumor Classification using Deep Learning

This project classifies breast tumors as malignant or benign using deep learning models.

## Dataset

The dataset used in this project is the **Breast Ultrasound Images Dataset (BUSI)**, available on [Kaggle](https://www.kaggle.com/datasets/anaselmasry/datasetbusiwithgt). It contains ultrasound images labeled as benign, malignant, or normal.

### Dataset Details:
- Number of images: **XXX**
- Categories: **Benign, Malignant, Normal**
- Preprocessing: **Resizing, Normalization, Data Augmentation**

## Models

We fine-tuned **DenseNet** and **EfficientNet**, two powerful convolutional neural network architectures, to classify breast tumor images. These models were chosen due to their strong feature extraction capabilities and efficiency in transfer learning.

### Training Details:
- **Dataset Split:** 80% training, 10% validation, 10% test
- **Optimizer:** Adam
- **Loss Function:** Categorical Cross-Entropy
- **Early Stopping:** Used to prevent overfitting

## Installation & Usage

To set up the project, follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/Tumor-Classification.git
cd Tumor-Classification

# Install dependencies
pip install -r requirements.txt

# Run the training script
python train.py
```

## Results & Performance

Our final model achieved **XX% accuracy on the test set**, with the following performance metrics:

| Metric     | Value |
|-----------|-------|
| Accuracy  | XX%   |
| Precision | XX%   |
| Recall    | XX%   |
| F1-score  | XX%   |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Dataset:** [Kaggle - Breast Ultrasound Images Dataset](https://www.kaggle.com/datasets/anaselmasry/datasetbusiwithgt)
- **Models Used:** DenseNet, EfficientNet
- **Frameworks:** TensorFlow, Keras, PyTorch (Specify based on your implementation)

## Contact

For questions or collaborations, feel free to reach out:
- **GitHub:** [YourUsername](https://github.com/yourusername)
- **Email:** your.email@example.com

