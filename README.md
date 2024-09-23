# Face Recognition

This project demonstrates a basic implementation of face recognition using Python and OpenCV.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [How it Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Face recognition technology has rapidly gained popularity across various applications. This project provides a simple solution to recognize faces in images using Python and OpenCV.

## Features

- Detect faces from an image or live webcam feed.
- Recognize faces using pre-trained models.
- Simple and easy-to-understand codebase for learning purposes.

## Requirements

Before running this project, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV
- NumPy
- dlib

You can install the necessary dependencies by running:

```bash
pip install -r requirements.txt
```

## Installation

To get started, clone this repository:

```bash
git clone https://github.com/T-Chaitanya/Face-recognition.git
cd Face-recognition
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

To detect and recognize faces in an image, use the following command:

```bash
python face_recognition.py --image <path_to_image>
```

For real-time face recognition via webcam, use:

```bash
python face_recognition.py --webcam
```

## How it Works

1. The system uses OpenCV to detect faces in images or video feeds.
2. The dlib library is used to extract facial landmarks, which are then converted into a face encoding.
3. The system compares new face encodings against a dataset of known encodings to identify the person.

## Contributing

Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/new-feature`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
