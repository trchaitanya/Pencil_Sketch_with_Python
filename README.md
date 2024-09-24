# Pencil_Sketch_with_Python

This project demonstrates how to transform a color image into a pencil sketch using Python and popular libraries like OpenCV. The result is a realistic, hand-drawn effect that mimics traditional pencil shading techniques.

# Features
Convert any image into a pencil drawing with a few lines of Python code. Utilizes image processing techniques like grayscale conversion, Gaussian blur, and blending to achieve the sketch effect. Easy to use: simply input your image and get an artistic pencil sketch as output. Code is modular and well-documented for easy customization and experimentation.

# Requirements
Python 3.x

OpenCV

# How it Works
Grayscale Conversion: The image is converted to grayscale to reduce the color information and prepare it for sketching.

Invert the Image : The grayscale image is inverted to highlight the details.

Blurring : A Gaussian blur is applied to smooth out the details and simulate the soft strokes of a pencil.

Final Blend : The original grayscale image is blended with the blurred, inverted version to create a pencil sketch effect.
