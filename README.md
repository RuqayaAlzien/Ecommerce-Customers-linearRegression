# Ecommerce Customer Data Analysis and Prediction using Linear Regression

## Overview

This project analyzes Ecommerce customer data to predict yearly spending based on various features using linear regression. The dataset used in this project is sourced from Kaggle.

## Dataset

The dataset contains the following features:
- **Email**: Customer's email address
- **Address**: Customer's physical address
- **Avatar**: Avatar image associated with the customer
- **Avg. Session Length**: Average session length of the customer in minutes
- **Time on App**: Average time spent on the app in minutes
- **Time on Website**: Average time spent on the website in minutes
- **Length of Membership**: Number of years the customer has been a member
- **Yearly Amount Spent**: Amount of money spent by the customer in a year (target variable)

## Project Structure

- `data/`: Contains the dataset file
- `notebooks/`: Jupyter notebooks with data analysis and model training
- `models/`: Saved models and model artifacts
- `scripts/`: Python scripts for data processing and modeling
- `README.md`: Project documentation

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ecommerce-linear-regression.git
    ```
2. Navigate to the project directory:
    ```bash
    cd ecommerce-linear-regression
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Jupyter Notebook

To explore the data and run the analysis, open the Jupyter notebook:

1. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open the notebook file located in the `notebooks/` directory and follow the steps to perform data analysis and linear regression.

### Python Scripts

You can also run the analysis using Python scripts:

1. Preprocess the data:
    ```bash
    python scripts/preprocess_data.py
    ```
2. Train the model:
    ```bash
    python scripts/train_model.py
    ```
3. Evaluate the model:
    ```bash
    python scripts/evaluate_model.py
    ```

## Results

The linear regression model was trained to predict the yearly amount spent by customers based on the features provided in the dataset. Key findings and performance metrics of the model are documented in the Jupyter notebook and the `results/` directory.

## Contributing

Contributions are welcome! Please create a pull request or open an issue for any changes or suggestions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [https://www.kaggle.com/code/ruqayaalzien/ecommerce-customers-linearregression] for providing the dataset.

## Contact

For any inquiries, please reach out to [ ruqayaalzien@gmail.com ]

