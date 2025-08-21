# mnist-digit

This project classifies handwritten digits (0-9) using the MNIST dataset. By leveraging image recognition with Convolutional Neural Networks (CNNs), the model can accurately predict digits drawn by users, enabling real-time digit recognition for educational and practical applications.

📂 Dataset#

The dataset used for this project is publicly available: 🔗 

It contains 70,000 grayscale images of handwritten digits, each sized 28x28 pixels, divided into 10 classes (digits 0-9).


⚠️ Challenges with the Dataset#

The digits are handwritten, so there is high variability in style and thickness.

Some digits look very similar (e.g., 1 and 7, 5 and 3), which can confuse the model.

Images are small (28x28), limiting the amount of detail for feature extraction.


✅ Solutions Applied#

Applied preprocessing (inverting, resizing, contrast enhancement) to standardize inputs.

Used Convolutional Neural Networks (CNNs) for effective feature extraction.

Employed data augmentation (rotation, shift, scaling) to improve model robustness.

Implemented a Gradio web interface for users to draw digits and get real-time predictions.

🚀 How to Use# 

🔴 Live Web App Use our demo on Hugging Face Spaces:

[👉 Try it Live](https://huggingface.co/spaces/Moaz-ai/55)
