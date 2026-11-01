<div align="center">

# DeepFER
### Deepfake Image Classification

**An experimental deep-learning project exploring real/fake facial-image classification with a Convolutional Neural Network.**

![Python](https://img.shields.io/badge/Python-0B1F33?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0F766E?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-0B1F33?style=flat-square&logo=opencv&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-0F766E?style=flat-square&logo=jupyter&logoColor=white)

</div>

---

## Project overview

DeepFER is a notebook-based image-classification experiment. It explores a workflow for distinguishing real and fake facial images using a CNN, including image preprocessing, model training, and prediction.

## Workflow

1. Prepare labeled facial-image data.
2. Preprocess images for model input.
3. Build and train a CNN model.
4. Generate predictions using the trained model.
5. Review notebook outputs and evaluate model behavior.

> This repository documents an experimental workflow. No accuracy or generalization claim is made here; assess performance using reproducible evaluation on a clearly defined test set.

## Technology stack

| Tool | Role |
| --- | --- |
| Python | Core programming language |
| TensorFlow / Keras | Deep-learning model development |
| OpenCV | Image processing |
| NumPy | Numerical operations |
| Matplotlib | Visualization |
| scikit-learn | Supporting machine-learning utilities |
| Jupyter Notebook | Interactive experimentation |

## Getting started

```bash
git clone https://github.com/rlaharira/DeepFER.git
cd DeepFER
```

Create and activate a virtual environment, then install the notebook dependencies:

```bash
python -m venv .venv
# macOS / Linux
source .venv/bin/activate
# Windows
# .venv\\Scripts\\activate

pip install tensorflow opencv-python numpy matplotlib scikit-learn jupyter
jupyter notebook DeepFER_project.ipynb
```

Run the notebook cells in order and update dataset paths to match your local setup.

## Dataset

The dataset is not included in this repository. Supply appropriately labeled real/fake facial-image data and ensure you have permission to use it. Keep private or licensed datasets out of version control.

## Reproducibility and responsible use

- Record dataset source, preprocessing choices, and train/validation/test splits.
- Evaluate on held-out data and inspect class balance.
- Avoid treating notebook results as proof that a detector will generalize to unseen content.
- Use this work for research and learning, not as a sole basis for consequential decisions.

## Repository contents

- `DeepFER_project.ipynb` — main experimental notebook
- `README.md` — project documentation

---

<div align="center">
  <sub>Exploring computer vision and deep learning through practical experimentation.</sub>
</div>
