# Computer_Vision-Projects
This repository contain my work on Computer Vision, to show my skills and ability to Image related project or task.

🎨 Pseudo Coloring Grayscale Images Using Autoencoder
This project implements a deep learning-based approach to convert grayscale images into colorized versions using an autoencoder architecture built with TensorFlow and OpenCV. The model is trained on a labeled landscape image dataset from Kaggle to learn meaningful representations for accurate color restoration.

📌 Project Overview
Objective: Colorize grayscale landscape images using a custom-trained autoencoder neural network.

Approach:

Used a convolutional autoencoder to encode grayscale image features and decode them into RGB color space.

Trained the model on a dataset of color landscape images, converting them to grayscale for supervised learning.

Evaluated results with visual inspection and standard image quality metrics.

🛠 Technologies & Libraries
Languages: Python

Frameworks: TensorFlow, Keras

Image Processing: OpenCV

Visualization: Matplotlib

Other Tools: NumPy, tqdm

📁 Dataset
Source: Kaggle landscape dataset (publicly available).

Images were resized and preprocessed to 150x150 resolution.

Grayscale versions were generated on-the-fly for training.

🧠 Model Architecture
Encoder: Multiple Conv2D + MaxPooling2D layers to extract spatial features.

Decoder: UpSampling2D and Conv2D layers to reconstruct color images from latent features.

Final layer outputs a 3-channel image corresponding to RGB.

📊 Results
The model demonstrated consistent colorization across diverse grayscale inputs.

Generalized well on unseen images with visually realistic outputs.

Suitable for applications such as:

Medical imaging enhancement

Black-and-white image restoration

Artistic or historical photo colorization

🚀 Getting Started
⚠️ Recommended: Run this notebook on a local machine or Google Colab Pro for better performance.
