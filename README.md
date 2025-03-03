# LGG-1p19q Deletion Classification

## Project Overview
This project aims to classify **1p/19q deletion** status in **low-grade gliomas (LGG)** using MRI scans and genetic data. The dataset contains **159 patients**, with MRI images and deletion status confirmed via pathology reports.

## Dataset Details
- **Patients**: 159 LGG cases
- **Deletion Categories**:
  - 102 cases with **1p/19q co-deletion**
  - 57 cases **without deletion**
- **MRI Sequences**: T1CE, T2
- **Preprocessing**: Image processing is required before classification.

## Methodology
1. **Data Preprocessing**: Image normalization, noise reduction, and augmentation.
2. **Feature Extraction**: Utilizing deep learning models or radiomics.
3. **Classification**: Training a machine learning model (CNN/MLP) for deletion classification.

## Expected Results
- Improved accuracy in predicting **1p/19q deletion**.
- Correlation analysis between **genetic and imaging** features.

## Future Work
- Exploring **multi-modal fusion** of MRI and genomic data.
- Implementing **attention-based** models for better interpretability.

## Requirements
- Python 3.x
- TensorFlow / PyTorch
- NumPy, OpenCV, scikit-learn

## Usage
```bash
# Clone repository
git clone <repo-link>
cd LGG-1p19q-classification

# Run preprocessing
python preprocess.py

# Train model
python train.py
```

## License
MIT License
