# Transfer Learning for Image Classification

## Hackathon Project – Dataset 2 (Reduced CIFAR-10)

### Project Overview
This project focuses on building an image classification model using Transfer Learning with EfficientNetB0. The model was trained and evaluated on a reduced CIFAR-10 dataset containing five image classes: airplane, automobile, bird, cat and dog.

The main objective was to improve image classification performance using a pre-trained deep learning model.

### Objectives
- Build an image classification model using Transfer Learning.
- Evaluate model performance using test accuracy and Macro F1-score.
- Compare generative AI tools for project development.

### Dataset
- **Dataset:** Reduced CIFAR-10
- **Classes:** Airplane, Automobile, Bird, Cat and Dog
- **Total Images:** 5,000
- **Images per Class:** 1,000
- **Original Image Size:** 32 × 32 RGB
- **Resized Image Size:** 224 × 224

### Technologies Used
- Python
- TensorFlow / Keras
- EfficientNetB0
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

### Methodology

1. **Data Exploration:** Explored the Reduced CIFAR-10 dataset and analysed image classes.
2. **Preprocessing:** Resized images from 32 × 32 to 224 × 224.
3. **Transfer Learning:** Used EfficientNetB0 pre-trained on ImageNet.
4. **Model Architecture:** Added Global Average Pooling, Dense, Dropout and Softmax layers.
5. **Data Augmentation:** Applied image augmentation to improve generalisation.
6. **Training:** Used a two-stage training approach with a frozen base model followed by fine-tuning.
7. **Evaluation:** Evaluated the final model using accuracy and Macro F1-score.

### Model Performance

| Evaluation | Result |
|---|---:|
| Stage 1 Validation Accuracy | 93.46% |
| Stage 2 Validation Accuracy | 95.62% |
| Improvement | 2.16% |
| Test Accuracy | 95.4% |
| Macro F1-score | 0.95 |

### Results and Findings
- EfficientNetB0 achieved strong image classification performance.
- Fine-tuning improved validation accuracy from 93.46% to 95.62%.
- Airplane and automobile classes achieved near-perfect classification.
- Most classification errors occurred between cat and dog images due to visual similarities.

### Generative AI Tools Used
- **ChatGPT:** Project structure and explanations.
- **GitHub Copilot:** Coding assistance.
- **Gemini:** Conceptual support.
- **DeepSeek:** Conceptual support.

### Future Improvements
- Experiment with alternative deep learning architectures.
- Use higher-resolution image datasets.
- Improve classification between visually similar animal classes.

### Conclusion
The project demonstrates the effectiveness of Transfer Learning for image classification. EfficientNetB0 achieved 95.4% test accuracy, while fine-tuning improved the overall validation performance.

---

**Project Type:** Hackathon / Deep Learning  
**Domain:** Artificial Intelligence and Computer Vision  
**Model:** EfficientNetB0
