# ☕ Coffee Bean Image Classification with CNN


## 🔍 Overview
This project focuses on classification of coffee beans using deep learning techniques. The beans are categorized based on their color — the primary visual feature — into four classes: Dark, Medium, Light, and Green. The goal is to build an accurate CNN-based model capable of distinguishing between these types with high precision.

## ⚡ GPU Optimization
If your system has a compatible GPU, TensorFlow will automatically detect it and use it to accelerate model training. This project is configured to take advantage of GPU hardware when available.
If no supported GPU is found, the code will safely fall back to the CPU, and everything will still run without any manual changes.

## 📁 Dataset

The dataset used in this project:

[Coffee Bean Dataset Resized – Kaggle](https://www.kaggle.com/datasets/gpiosenka/coffee-bean-dataset-resized-224-x-224)

It contains labeled images of coffee beans divided into 4 categories:

- **Dark**
- **Medium**
- **Light**
- **Green**

## 🚀 Getting Started

1. **Download the [Coffee Bean Dataset Resized – Kaggle](https://www.kaggle.com/datasets/gpiosenka/coffee-bean-dataset-resized-224-x-224)**

2. Make sure to organize the data into the following directory structure:

   * `cnn-coffee-beans-classifier/`
     * `cnn_project.ipynb`
     * `coffee_bean_data/`
       * `train/`
       * `test/`
       * `Coffee Bean.csv`

3. **Install Anaconda**
4. **Go to Anaconda Navigator and Create a Custom Environment** ( Select Python packages )
5. **Manually Install the Required Libraries**
   
   After creating and activating your custom environment, manually install all the necessary libraries used in this project, such as TensorFlow, Keras, Matplotlib, etc.

6. **Install and Launch Jupyter in Your Custom Environment**
7. **Locate the Directory Where You Saved the Project and Run .ipynb file**






