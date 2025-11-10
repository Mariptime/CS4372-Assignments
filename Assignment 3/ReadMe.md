#  This Project is a Homework Assignment for CS 4372.501
## MobileNetV2 Image Classification (Transfer Learning) - Dog Breed Identification

This project implements an image classifier using **TensorFlow Keras** with a **MobileNetV2** backbone and fine-tuning support.  It is designed for flexible experimentation — you can tune learning rate, dropout, number of unfrozen layers, filters and kernel ssize.

---

## Dependencies

Ensure you have **Python 3.9+** and **conda** or **pip** installed. Installing packages in a virual environment is recommended.

### Required Packages

You can install all the required packages at once with:

`pip install tensorflow==2.15.0 numpy pandas matplotlib pillow scikit-learn requests jupyterlab`

---

## Project Structure

```
project_root/
│
├── results/ (will be created on run)
│   ├── history_run_1.png
│   ├── history_run_2.png
│   ├── sample_predictions_run_1.png
│   └── ...
|
├── runtime_data/ (will be created on run)
│   └── test/*
│   └── train/*
│   └── ...
|
├── MainCode.ipynb
│
└── README.md
```

---

## How to Run and Compile the Notebook

### 1. Install dependencies

`pip install tensorflow==2.15.0 numpy pandas matplotlib pillow scikit-learn requests jupyterlab`

### 2. Launch Notebook

`jupyter notebook`

Then open the notebook file: `MainCode.ipynb`

or

Use VSCode with jupyter notebooks extension

---

## Viewing Results

Once the training completes, you’ll find output images under `results/`. But previews will also be available to view in the original notebook.

Results include a history plot showing training and testing accuracy and loss as a function of multiple iterations. You can also see at least 25 test data points, including the data, the true label, and the predicted label. You are also able to preview how each varied model build predicted at the end, with their respective results.

---

##  Contributors

These works are a collaboration between the following main contributors:

*  **@mariptime** - Akshay Nagarajan

*  **@vaipos** - Vaishnavi Pasumarthi

CS 4372.501 - Assignment 2

Anurag Nagar - Fall 2025