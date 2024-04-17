# Face Detection Application

This repository contains the code and documentation for a face detection application based on the VGG16 neural network architecture. The application is designed to detect faces in images using deep learning techniques.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)

- [License](#license)

## Introduction

The face detection application utilizes the VGG16 convolutional neural network to detect faces in images.
Whole process from implemetation to results is presented in this file [FaceDetection.pdf](https://github.com/BCiucka/FaceDetection/files/15010625/FaceDetection.pdf).



## Installation

To install and run the face detection application, follow these steps:

1. Clone this repository to your local machine using Git:

    ```bash
    git clone https://github.com/yourusername/face-detection.git
    ```

2. Navigate to the project directory:

    ```bash
    cd face-detection
    ```

3. Install the required dependencies. It's recommended to use a virtual environment:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once the installation is complete, you can use the face detection application as follows:

1. Prepare your input images: Place the images you want to analyze in the `input_images` directory.

2. Run the face detection script:

    ```bash
    python detect_faces.py
    ```

3. View the results: The detected faces will be highlighted in the output images saved in the `output_images` directory.



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
