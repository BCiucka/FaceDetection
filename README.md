# Face Detection Application

This repository contains the code and documentation for a face detection application based on the VGG16 neural network architecture. The application is designed to detect faces in images using deep learning techniques.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The face detection application utilizes the VGG16 convolutional neural network to detect faces in images. It follows a multi-phase training process, as described in the accompanying technical document ([Bionika.pdf](Bionika.pdf)), to achieve accurate face detection results.

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

## Contributing

Contributions to the face detection application are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
