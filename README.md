# Data Imputation Program - Version 3.6

## Introduction
This program is designed for imputing missing values in a dataset using machine learning methods. In Version 3.6, we utilize the Bayesian Ridge estimator for data imputation. The program handles multivariate data, normalizes it, performs imputation, and provides analysis on selected columns.

## Usage
To utilize this program, follow these steps:

1. **Install Required Libraries:** Ensure you have the necessary libraries installed. You can install them using pip:
   - `pandas`
   - `seaborn`
   - `scikit-learn`

2. **Prepare Your Dataset:** Place your dataset in a CSV file named `AMR-and-NSH-Buoy-Data1394-normalized-mice-bayesian-ridge.csv` within the `clean-xls-files` directory.

3. **Execute the Program:** Open the `main.py` file and run it using a Python interpreter. There's no need to specify `python main.py`, as the script can be executed directly.

4. **Program Tasks:**
   - Load the dataset from the specified CSV file.
   - Separate date and time information.
   - Identify missing values for each column.
   - Configure the Bayesian Ridge estimator for imputation.
   - Normalize the dataset (optional, currently commented out).
   - Generate date and time values.
   - Perform iterative imputation with Bayesian Ridge.
   - Analyze and visualize the distribution of selected columns.
   - Save the imputed dataset to a new CSV file in the `multivariate-method-results` directory.

5. **Imputed Dataset:** The final imputed dataset will be saved as `AMR-and-NSH-Buoy-Data1394-normalized-mice-bayesian-ridge.csv` in the `multivariate-method-results` directory.

## Customization
Customize this program by:
- Adjusting the dataset file name and location if necessary.
- Enabling or disabling data normalization as needed.
- Modifying the choice of estimator for imputation (currently set to Bayesian Ridge) by replacing it with other scikit-learn estimators.

Feel free to explore and modify the code to suit your specific data imputation requirements.

## Version History
- Version 3.6: Bayesian Ridge estimator for imputation, added documentation (current version).

For any questions or issues, please contact ehsanasgharzadeh.asg@gmail.com.
