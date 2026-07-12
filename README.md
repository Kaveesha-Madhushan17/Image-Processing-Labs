# Image Processing Labs

This repository contains a comprehensive set of Jupyter Notebook labs for learning image processing and computer vision concepts using Python. The notebooks progress from basic image representation to advanced topics such as segmentation, recognition, transfer learning, and frequency-domain filtering.

## Overview

These labs are designed for students and practitioners who want to build a strong foundation in digital image processing. The workflow starts with understanding images as arrays of numbers and gradually moves into practical techniques used in real-world computer vision systems.

## What You Will Learn

By completing the labs in this repository, you will explore:

- How digital images are represented as numeric matrices
- Basic image transformations such as resizing, cropping, and interpolation
- Brightness, contrast, and illumination adjustment
- Thresholding and segmentation techniques
- Noise removal and structure-preserving filtering
- Edge detection, corners, and structural features
- Unsupervised and supervised digit recognition
- Transfer learning and fine-tuning with deep learning
- Frequency-domain filtering for artifact removal

## Repository Structure

- Lab 01 - Seeing Images as Numbers & Understanding Basic Transformations
  - Introduces pixels, grayscale conversion, resizing, and image representation
  - Includes notebooks such as Image_Processing_Lab_01.ipynb and E_21_245_Lab_01.ipynb

- Lab 02 - Illumination, Contrast & Thresholding Fundamentals
  - Covers brightness adjustment, contrast enhancement, and threshold-based segmentation

- Lab 03 - Noise Removal & Structure Preservation
  - Focuses on salt-and-pepper noise, filtering methods, and preserving meaningful image structure

- Lab 04 - Segmentation & Image Restoration
  - Explores global and adaptive thresholding, segmentation, and restoration concepts

- Lab 05 - Edges, Corners & Structural Features
  - Introduces feature extraction methods such as edge and corner detection

- Lab 06 - Unsupervised & Supervised Digit Recognition
  - Uses digit data to demonstrate clustering and classification approaches
  - Includes the dataset file Digits_Lab_01.csv

- Lab 07 - Transfer Learning & Fine-Tuning
  - Demonstrates the use of pretrained deep learning models for image classification tasks

- Lab 08 - Frequency-Domain Filtering for Artifact Removal
  - Introduces Fourier transforms and filtering in the frequency domain

## Environment Setup

This project uses Python and Jupyter notebooks. The repository includes a Pipfile with Python 3.12 as the target version.

### Option 1: Using Pipenv

```bash
pipenv install
pipenv shell
```

### Option 2: Install dependencies manually

If you prefer not to use Pipenv, make sure the following packages are installed:

- opencv-python
- numpy
- matplotlib
- pandas
- scikit-learn
- pillow
- scipy
- torch
- ipykernel

You can install them using:

```bash
pip install opencv-python numpy matplotlib pandas scikit-learn pillow scipy torch ipykernel
```

## Running the Notebooks

1. Open the repository in Jupyter Notebook or VS Code with the Python/Jupyter extensions enabled.
2. Start the notebook environment.
3. Open any lab notebook in the desired folder.
4. Run the cells in order to follow the experiments and explanations.

For better notebook organization, you may also register a dedicated kernel:

```bash
python -m ipykernel install --user --name image-processing --display-name "Python (Image Processing)"
```

## Notes and Tips

- Keep the folder structure intact when running notebooks, especially for labs that reference local image files or CSV data.
- Some notebooks may require internet access, particularly those that download or fetch data.
- GPU support is helpful for Lab 07, but CPU execution is also possible for smaller experiments.
- If a notebook fails to find a file, verify that you are running it from the correct folder or adjust the file path accordingly.

## Suggested Learning Order

It is recommended to complete the labs in the following order:

1. Lab 01
2. Lab 02
3. Lab 03
4. Lab 04
5. Lab 05
6. Lab 06
7. Lab 07
8. Lab 08

## License

This project is intended for educational purposes and is suitable for learning and experimentation.
