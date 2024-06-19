# CNN Cancer Detection
This project contains a Jupyter notebook, [`cancer_detection.ipynb`](cancer_detection.ipynb), which implements a Convolutional Neural Network (CNN) for cancer detection. 

## Notebook Content

- **Data Preprocessing**: This section covers the preprocessing steps required for the cancer detection dataset, including data loading, data augmentation, and data splitting.
- **Model Architecture**: This section defines the architecture of the cancer detection model using the Keras Sequential API. It includes the layers, activation functions, and regularization techniques used in the model. It also covers the training process of the cancer detection model, including compiling the model, defining the loss function and optimizer, and fitting the model to the training data.
- **Results & Analysis**: This section evaluates the performance of the trained model on the training and validation data, including calculating accuracy, loss, and recall.
- **Test Model**: This section runs the model on test data and creates a submission.
- **Conclusion**: This section offers insight to how the submission held up and what could be done to improve the accuracy of the model.

## Dataset

The dataset used in this project will be stored in a created directory called `data/`. It contains training and testing data, along with the labels. To get the data, either download from [Kaggle](https://www.kaggle.com/competitions/histopathologic-cancer-detection/data) or use the CLI call from the notebook and unzip the file.

## Usage

To run the notebook, open it in Jupyter and execute all cells.

## Requirements

Run the installs within the notebook.