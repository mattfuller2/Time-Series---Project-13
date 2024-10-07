# Time-Series---Project-13

# Sweet Lift Taxi: Taxi Order Prediction

### Description
The **Sweet Lift Taxi** company aims to predict the number of taxi orders for the next hour at airports to attract more drivers during peak hours. This project involves building a predictive model to forecast the number of orders using historical data. The model's performance is evaluated using the **RMSE** metric, with a goal to achieve an RMSE of no more than **48** on the test set.

### Project Structure
- **notebook.ipynb**: Contains the entire workflow, including data preprocessing, exploratory data analysis (EDA), model training, and evaluation.
- **/datasets/taxi.csv**: The dataset used in this project, containing historical taxi orders with the target column `num_orders`.
- **/output/**: Stores model predictions, evaluation metrics, and visualizations.

### Objectives
The primary objectives of the project are:
1. **Data Resampling**:
   - Resample the taxi order data by one hour to prepare it for modeling.
   
2. **Exploratory Data Analysis (EDA)**:
   - Analyze the dataset to understand trends and patterns.
   
3. **Model Training**:
   - Train different machine learning models with various hyperparameters to predict the number of taxi orders.
   - Use 90% of the dataset for training and 10% for testing.

4. **Model Evaluation**:
   - Evaluate the models using the RMSE metric.
   - Ensure that the final model achieves an RMSE of no more than **48** on the test set.

### Data Description
The dataset is stored in the `/datasets/taxi.csv` file and contains historical data on taxi orders at airports. The target variable for the prediction task is the `num_orders` column, which represents the number of taxi orders in a given time interval.

### Findings
- After resampling the data by one hour and analyzing it, significant trends were identified that helped in feature engineering.
- The final model achieved an RMSE of **XX** (to be updated), meeting the goal of an RMSE less than **48**.
- The model predictions can be used to inform the company of peak hours, allowing them to attract more drivers during high-demand periods.

### Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sweet-lift-taxi-order-prediction.git
2. Install the required dependencies
   pip install -r requirements.txt
3. Launch Jupyter Notebook
   jupyter notebook
