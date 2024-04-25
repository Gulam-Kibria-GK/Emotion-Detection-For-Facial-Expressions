# Emotion Detection For Facial Expressions

The Emotion Detection For Facial Expressions project focuses on emotion detection by measuring facial features using OpenCV (Python). This system predicts and recognizes the expressions of individuals facing the camera by leveraging Convolutional Neural Networks (CNNs) trained on facial images. It detects faces, extracts features, and models emotional expressions in real-time.

## About

Facial expressions are a natural way to communicate emotional states and intentions. The facial expression detection method consists of three main steps: face detection, feature extraction, and modeling. This project provides a simple and accurate solution for detecting human emotions, contributing to the development of emotion detection systems in the digital era.

## Contents

1. [About](#about)
2. [Files](#files)
3. [Training](#training)
4. [Testing with Face Landmarks](#testing-with-face-landmarks)
5. [Testing without Face Landmarks](#testing-without-face-landmarks)
6. [Dependencies](#dependencies)
7. [Additional Resources](#Additional-Resources)
8. [Author](#author)

## Files

1. **Dataset**: Dataset used for training the emotion detection model.
2. **[Emotion Detection For Facial Expressions.pdf](https://github.com/GK-CPP/Emotion-Detection-For-Facial-Expressions/blob/master/Emotion%20Detection%20For%20Facial%20Expressions.pdf)**: Documentation providing details about the project.
3. **Emotion_2.h5**: Pre-trained model weights saved in HDF5 format.
4. **Training.ipynb**: Jupyter Notebook containing the code for training the CNN model.
5. **Test_with_face_landmarks.ipynb**: Jupyter Notebook for testing the trained model with face landmarks.
6. **Test_with_out_face_landmarks.ipynb**: Jupyter Notebook for testing the trained model without face landmarks.
7. **haarcascade_frontalface_default.xml**: XML file containing the pre-trained Haar Cascade classifier for face detection.
8. **shape_predictor_68_face_landmarks.dat**: Data file containing the shape predictor for detecting 68 facial landmarks.
9. **README.md**: This file, providing an overview of the project.

## Training

The `Training.ipynb` notebook contains the code for training the CNN model using the provided dataset. It includes data preprocessing, model architecture definition, training process configuration, and model evaluation.

## Testing with Face Landmarks

The `Test_with_face_landmarks.ipynb` notebook demonstrates how to use the trained model for real-time emotion detection with face landmarks. It utilizes OpenCV for face detection and Dlib for detecting facial landmarks. The system captures video input from a camera and overlays emotion labels on detected faces along with facial landmarks in real-time.

## Testing without Face Landmarks

The `Test_with_out_face_landmarks.ipynb` notebook showcases how to use the trained model for real-time emotion detection without face landmarks. Similar to the previous method, it utilizes OpenCV for face detection. The system captures video input from a camera and overlays emotion labels on detected faces in real-time.

## Dependencies

This project requires the following dependencies:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV
- Dlib
- Jupyter Notebook

You can install these dependencies using pip:

```bash
pip install tensorflow keras numpy matplotlib opencv-python dlib jupyter
```

## Additional Resources

- [PDF](https://github.com/GK-CPP/Emotion-Detection-For-Facial-Expressions/blob/master/Emotion%20Detection%20For%20Facial%20Expressions.pdf)

- [Project Trailer](https://www.youtube.com/watch?v=V0sRD_gn86Q) <br> <br>
  [![Gender-Classification-using-CNN](https://img.youtube.com/vi/V0sRD_gn86Q/0.jpg)](https://www.youtube.com/watch?v=V0sRD_gn86Q)

## Author

Gulam Kibria Chowdhury<br>
Software Developer || Competitive Programmer<br>
Sylhet, Bangladesh<br>
Gmail: gkchowdhury101@gmail.com<br>
