# Image Classification for a City Dog Show

## Project Overview
This project focuses on using Python to classify dog images for a citywide dog show registration system. The goal is to ensure only valid dog images are registered and to identify the breeds of the dogs. By leveraging a pre-trained convolutional neural network (CNN), the project applies Python programming skills to test different image classification models and evaluate their performance.

---

## Project Objectives
1. **Validate Images**: Ensure the uploaded images are of dogs using pre-trained CNN models.
2. **Classify Dog Breeds**: Identify the breed of the dog from the image.
3. **Evaluate Classifier Performance**: Compare different CNN architectures (AlexNet, VGG, ResNet) based on:
   - Accuracy in classification.
   - Runtime performance.
4. **Analyze Trade-Offs**: Explore the trade-off between classification accuracy and computational runtime.

---

## Tools and Technologies
- **Python**: Programming language used for implementing the solution.
- **Convolutional Neural Networks (CNNs)**:
  - **AlexNet**
  - **VGG**
  - **ResNet**
- **ImageNet Dataset**: Pre-trained models trained on 1.2 million images.
- **Classifier Function**: Provided as `classifier.py` for using the pre-trained CNN models.

---

## Project Workflow
1. **Input**: Dog images submitted during the registration process.
2. **Validation**: Use the provided `classifier.py` to determine if the image contains a dog.
3. **Classification**:
   - Identify the breed of the dog using pre-trained CNNs.
   - Compare accuracy across CNN architectures.
4. **Performance Evaluation**:
   - Measure accuracy of predictions.
   - Time the runtime for each CNN architecture.
   - Determine the trade-off between runtime and accuracy.
5. **Output**:
   - Indicate whether the uploaded image is of a dog.
   - Classify the dog's breed (if applicable).
   - Log performance metrics for each CNN.

---

## Key Features
- Pre-trained CNNs (AlexNet, VGG, ResNet) for image classification.
- Ability to handle images with similar-looking dog breeds.
- Runtime and accuracy trade-off analysis for algorithm selection.
- Comprehensive Python-based solution utilizing:
  - Loops, functions, and conditionals.
  - Performance measurement with `time` library.


## Acknowledgements
ImageNet Dataset: For pre-trained CNN models.
Udacity AI Programming with Python Nanodegree: For project guidance and resources.
Classifier.py: Provided as a functional tool to simplify CNN usage.
