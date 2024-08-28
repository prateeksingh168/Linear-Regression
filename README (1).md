# Iris Dataset Splitter

This project is a Python script to split the Iris dataset into training and testing sets. The script loads the Iris dataset, splits it into training and testing sets using an 80-20 split, and then prints the number of samples in each set.

## How to Use

### Prerequisites

- Python 3.x installed on your system.
- The `scikit-learn` library installed. You can install it using pip:

    ```bash
    pip install scikit-learn
    ```

### Running the Script

1. **Save the script** as `iris_splitter.py` or any name you prefer.
2. **Open a terminal or command prompt**.
3. **Navigate to the directory** where the script is saved.
4. **Run the script** by executing the following command:

    ```bash
    python iris_splitter.py
    ```

### Script Details

The script performs the following steps:

1. **Load the Iris Dataset**:
   - The Iris dataset is loaded from the `sklearn.datasets` module.

2. **Split the Dataset**:
   - The dataset is split into training and testing sets using an 80-20 split.
   - The `train_test_split` function from `sklearn.model_selection` is used for splitting the data.
   - The `random_state` parameter is set to `42` to ensure reproducibility.

3. **Print the Number of Samples**:
   - The script prints the number of samples in the training and testing sets.

### Example

When you run the script, the output will display the number of samples in the training and testing sets. For example:

```bash
Number of samples in the training set: 120
Number of samples in the testing set: 30
