# DeepFER — Deepfake Image Classification

A deep-learning project that explores classifying facial images as **real** or **fake** using a Convolutional Neural Network (CNN). The project is provided as a Jupyter Notebook.

## Project overview

The notebook documents an image-classification workflow, including image preprocessing, model training, and prediction.

## Technologies

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/rlaharira/DeepFER.git
   cd DeepFER
   ```

2. Install the libraries used by the notebook (if they are not already available):

   ```bash
   pip install tensorflow opencv-python numpy matplotlib scikit-learn jupyter
   ```

3. Launch Jupyter and open the notebook:

   ```bash
   jupyter notebook DeepFER_project.ipynb
   ```

4. Follow the notebook cells in order. Configure the dataset paths to match your local dataset before running the training and evaluation steps.

## Dataset

The notebook is intended to work with labeled real/fake facial-image data. Make sure you have the appropriate dataset and permission to use it; dataset files are not included in this repository.

## Notes

This is an experimental project. Model performance depends on the dataset, preprocessing, training setup, and evaluation method. Review the notebook outputs when assessing results.

## Repository

[View the source code and notebook](https://github.com/rlaharira/DeepFER)
