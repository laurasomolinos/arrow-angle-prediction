# Arrow Angle Prediction (Computer Vision)

This project focuses on predicting the orientation angle of arrows from images using deep learning techniques.

APRENDIZAJE AUTOMÁTICO II - Grado Ciencia de Datos e Inteligencia Artificial (UPM)

The problem is formulated as a regression task, where the model predicts the angle of the arrow using a sine/cosine representation.

## Project Overview

The objective is to estimate the orientation of arrows in images.

Instead of directly predicting the angle, the model predicts:

- sin(angle)
- cos(angle)

This avoids discontinuities and improves prediction stability.

## Approach

- Image preprocessing and resizing
- Feature extraction using Convolutional Neural Networks (CNNs)
- Regression model for angle prediction
- Conversion from sin/cos predictions to final angle

## Model

- CNN-based architecture
- Regression output (2 values: sin, cos)
- Loss functions adapted for regression tasks

## Technologies

- Python
- PyTorch
- NumPy
- Matplotlib

## Project Structure

```text
arrow-angle-prediction.
├── arrow_angle_prediction.ipynb
├── README.md
├── requirements.txt
└── data/
```

## How to Run

Install dependencies:
```bash
pip install -r requirements.txt```

run: 
```bash
jupyter notebook```

## Notes

The dataset is not included due to size constraints.

Place the images inside the data/ folder to run the project.
