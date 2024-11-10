# ML Project : Distracted Driver Recognition Project

This project aims to classify images of drivers into different categories based on their activities, such as safe driving, texting, talking on the phone, etc. The project uses various machine learning algorithms, including SVM, KNN, and Random Forest, as well as deep learning techniques with Convolutional Neural Networks (CNN).

# Project Links
- [Project on Kaggle](https://www.kaggle.com/code/arihantdebnath/distracted-driver?scriptVersionId=206373202)
- [Project on Collab](https://colab.research.google.com/drive/1tifgr94NkAfzIR9G3cl32NKJ98T15rsS?usp=sharing)

## Project Structure

- `distracted-driver.ipynb`: Jupyter Notebook containing the implementation of the project.
- `requirements.txt`: List of required Python packages.
- `README.md`: Project documentation.

## Requirements

- Python 3.6 or higher
- Conda (optional, for creating a virtual environment)

## Installation

### Using Conda

1. Create a new conda environment:
    ```bash
    conda create --name distracted-driver python=3.8
    ```

2. Activate the environment:
    ```bash
    conda activate distracted-driver
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Using Python Virtual Environment

1. Create a virtual environment:
    ```bash
    python -m venv distracted-driver-env
    ```

2. Activate the virtual environment:
    ```bash
    # On Windows
    distracted-driver-env\Scripts\activate

    # On macOS/Linux
    source distracted-driver-env/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook distracted-driver.ipynb
    ```

2. Run the cells in the notebook to execute the code and see the results.

## Algorithms Used

- **Support Vector Machine (SVM)**: Used for classification with and without PCA.
- **K-Nearest Neighbors (KNN)**: Used for classification and comparison with SVM.
- **Random Forest**: Used for classification and comparison with other algorithms.
- **Convolutional Neural Network (CNN)**: Used for feature extraction and classification.

## Results

The project evaluates the performance of different algorithms using metrics such as accuracy, confusion matrix, and classification report.

## Project by:
ARIHANT DEBNATH [RA2211003011033] <br>
DIVA MERJA [RA2211003011034] <br>
MAKADIA YAKSH VIJAYAKUMAR[RA2211003011035] <br>
KRISHNA WADHWANI[RA2211003011045] <br>

## License

This project is licensed under the MIT License.
