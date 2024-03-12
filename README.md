# Name Entity Recognition and Classification

## Table of Contents

- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Installation Instructions](#installation-instructions)
- [Resources](#resources)
- [License](#license)
- [Conclusion](#conclusion)
- [Contact](#contact)

## Introduction

This repository hosts the implementation and documentation for a machine learning project aimed at interpreting doctor notes through Name Entity Recognition (NER) and Classification techniques. The objective is to categorize medical notes into "Others" and "Syndrome" to facilitate quicker and more accurate healthcare decisions.

## Environment Setup

**Prerequisites**: Ensure Python 3.6 or newer is installed on your system.

1. **Create a Virtual Environment**:
    - Install `virtualenv` if you prefer it over the built-in `venv` (optional):
        ```bash
        pip install virtualenv
        ```
    - Create the environment:
        - With `venv` (Python 3.3+):
            ```bash
            python -m venv env
            ```
        - Or, with `virtualenv`:
            ```bash
            virtualenv env
            ```
    - Activate the environment:
        - Windows: `env\Scripts\activate`
        - Unix/MacOS: `source env/bin/activate`
    - To deactivate: `deactivate`

2. **Dependencies**:
    Ensure all dependencies are listed in `requirements.txt`. Install them using:
    ```bash
    pip install -r requirements.txt
    ```

## Installation Instructions

To use this project, clone the repository and set up the environment as follows:

1. **Clone the Repository**:
    ```bash
    https://github.com/Imran-ml/Name-Entity-Recognition-and-Classification.git
    ```
2. **Setup the Environment**:
    - Navigate to the project directory and activate the virtual environment.
    - Install the dependencies from `requirements.txt`.

## Resources

- **Kaggle Notebook**: [View Notebook](https://www.kaggle.com/code/muhammadimran112233/name-entity-recognition-and-classification)
- **Dataset**: [View Dataset](https://www.kaggle.com/datasets/muhammadimran112233/clinical-documents-on-syndromes-disease)

## License

This project is made available under the MIT License.

## Conclusion

We applied different techniques on the data preparation and then features extraction. We used TF-IDF technique to extract the features from the text but the models was not giving good results. We changed the features extraction technique to Sequence extractor using tensorflow and we got the good results. Data preprocessing, data extraction and hyper parameter tuning helped to boost the performance of RNN but Random forest did not performed well.

Well about the hyper parameters tuning, we don’t need to set different hyper parameters, train the model and show the results. To do this what we need to do, we tune the hyper parameters according to problem, we train and test and know how the model giving results in deep learning. And in Random forest model, we can use GRID SEARCH approach that train the model on all the given hyper parameters and select the best parameters to train the final model.

Hyper parameters for RNN,
We choose the different number of parameters but after tuning, we got best hyper parameters to get the good results. We used Sigmoid activation function as we need only one output. Sigmoid function helps to get one output for binary problem. We used binary cross entropy as our problem is to classify only two classes. RMSPROP optimizer helps to get the good results. We change and test different epochs and batch sizes but 20 epochs and 500 batch size is good to get the good results as well.

Hyper parameters for RF,
To get the best parameters of random forest model, we used grid search which take different parameters every time and train the model. Finally grid search train the model on the best parameters. These are the best parameters for RF model: {'n_estimators': 200, 'max_features': 'sqrt', 'max_depth': 8, 'criterion': 'gini'}

We got good results on the RNN because it remember each and every information of previous times.

## Contact

- **Name**: Muhammad Imran Zaman
- **Email**: [imranzaman.ml@gmail.com](mailto:imranzaman.ml@gmail.com)
- **Professional Links**:
    - Kaggle: [Profile](https://www.kaggle.com/muhammadimran112233)
    - LinkedIn: [Profile](linkedin.com/in/muhammad-imran-zaman)
    - Google Scholar: [Profile](https://scholar.google.com/citations?user=ulVFpy8AAAAJ&hl=en)
    - YouTube: [Channel](https://www.youtube.com/@consolioo)
- **Project Repository**: [GitHub Repo](https://github.com/Imran-ml/Name-Entity-Recognition-and-Classification.git)
