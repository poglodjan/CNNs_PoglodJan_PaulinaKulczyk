# CNNs for CINIC-10 – Deep Learning Image Classification Project

This project explores various Convolutional Neural Network (CNN) architectures for image classification using the **CINIC-10 dataset**. Our experiments include both classic and modern deep learning models, and we evaluate their performance using metrics such as accuracy, loss, and F1-score. We also propose an ensemble learning approach that achieves state-of-the-art results in our setup.

---

## Repository Contents

### 📘 `CNN_overview.ipynb`
A general introduction and overview of our deep learning pipeline using CNNs. This notebook includes:
- Data loading and preprocessing
- Simple baseline CNN architectures (e.g. single and double Conv2D)
- Early performance analysis with and without augmentation

### `Augmentation_technique_presentation.ipynb`
Code implementations of various data augmentation techniques with examples and visualizations of the transformations applied.

This notebook tests **modern and deeper models**:
- ResNet18 / ResNet34
- VGG16
- GoogLeNet
We analyze their performance on the CINIC-10 dataset and compare results in terms of validation loss, accuracy, and generalization.

### 📘 `CCN_ensemble_models.ipynb`
We propose an **ensemble learning** approach using the best-performing models. This notebook combines CNNs trained on different augmentations (e.g., sepia, flipped) and specialized models to improve classification—especially for challenging classes like cats and dogs.

### 📘 `CNNetworks_Project.pdf`
A detailed report, documenting our work, methodology, experiments, and findings. It includes:
- Overview of our research
- Model architectures used
- Training process and results
- Performance evaluation and analysis

### 📘 `results_presentation.pdf`
A concise slide deck summarizing our methodology, model comparisons, confusion matrices, and final conclusions from the experiments.

---

## 🔬 View Experiments on Colab
To run and explore the main notebook interactively, visit:

🔗 [Google Colab Link](https://colab.research.google.com/drive/1Bu_62k0sNnbOXXKXIbVEucYF2xCjNODq#scrollTo=c9QJATChgJRv)

---

## Highlights
- Dataset: CINIC-10 (90k training, 90k validation, 90k test)
- Architectures: Basic CNNs, Deep CNN, VGG, ResNet18/34, GoogLeNet
- Techniques: Data Augmentation, Batch Normalization, Dropout, Ensemble Learning
- Best result: **~78.5% accuracy on the test set** using ensemble models.

---
