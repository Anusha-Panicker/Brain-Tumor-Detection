# 🧠 Brain Tumor Prediction

A comprehensive deep learning project comparing Three different CNN architectures for brain tumor classification on medical imaging datasets.

## 📋 Overview

This project implements and compares three different deep learning models for brain tumor detection and classification:

- **Custom CNN Architecture** - A lightweight CNN model designed from scratch for efficiency
- **ResNet50** - A pre-trained deep residual network
- **EfficientNetB3** - An optimized pre-trained efficient network

The goal is to build a model with fewer parameters and fast training time while maintaining competitive accuracy.

## 📊 Dataset

- **Total Images**: 7,200+
- **Training Set**: 5,600 images
- **Testing Set**: 1,600 images
- **Classes**: Brain tumor classification categories
- **Format**: High-resolution medical imaging data

## 🏗️ Project Structure

```
.
├── ResNet50.ipynb                 # ResNet50 implementation and evaluation
├── EfficientNetB3.ipynb           # EfficientNetB3 implementation and evaluation
├── Custom CNN Architecture.ipynb  # Custom lightweight CNN model
├── Comparison.ipynb               # Side-by-side model comparison and results
└── README.md                      # This file
```

## 🎯 Key Objectives

✅ Build an efficient custom CNN model with minimal parameters  
✅ Compare performance across three different architectures  
✅ Achieve high accuracy on brain tumor classification  
✅ Optimize training time and computational resources  
✅ Provide detailed performance metrics and visualizations  

## 📈 Model Comparison

| Metric | Custom CNN | ResNet50 | EfficientNetB3 |
|--------|-----------|----------|----------------|
| Parameters | Lower | High | Medium |
| Training Time | Fast | Slower | Moderate |
| Accuracy | 94.1250% | 91.87% | 90.31% |
| Inference Speed | Fast | Moderate | Good |

*Note: Run the Comparison.ipynb notebook to see the complete performance metrics*

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required libraries (see requirements.txt)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/anirudhpatekar19906/Brain-Tumor-Prediction.git
   cd Brain-Tumor-Prediction
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Open Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

2. **Run the notebooks in order**
   - Start with individual model notebooks: `ResNet50.ipynb`, `EfficientNetB3.ipynb`, `Custom CNN Architecture.ipynb`
   - View comprehensive comparison: `Comparison.ipynb`

## 📦 Dependencies

- TensorFlow / PyTorch
- NumPy
- Pandas
- Matplotlib / Seaborn
- scikit-learn
- Jupyter

Install all dependencies:
```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn jupyter
```

## 📊 Results

The `Comparison.ipynb` notebook contains:
- Side-by-side model performance metrics
- Training vs validation accuracy curves
- Confusion matrices
- Precision, recall, and F1-scores
- Inference time comparisons

## 🔍 Key Findings

- Custom CNN achieved comparable accuracy with significantly fewer parameters
- EfficientNetB3 provided the best balance between accuracy and efficiency
- ResNet50 achieved highest accuracy but with increased computational cost

## 💡 Methodology

1. **Data Preprocessing**: Normalization and augmentation
2. **Model Training**: Cross-validation and hyperparameter tuning
3. **Evaluation**: Multiple metrics for comprehensive assessment
4. **Comparison**: Detailed performance analysis across architectures

## 📚 References

- ResNet: Deep Residual Learning for Image Recognition
- EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks
- Transfer Learning for Medical Imaging

## 👤 Author

Anirudh Pandurang Patekar

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Brain Tumor Dataset source
- TensorFlow and PyTorch communities
- Contributors and reviewers

---------------------------------------------------------------------------------------------

**Note**: This project is for educational and research purposes. Always consult with medical professionals for actual clinical applications.