# Inventory Optimization and Demand Forecasting System 
## Project By Arman Rashid
### Description
This project provides a Python-based solution for inventory optimization and demand forecasting. It helps businesses efficiently manage their inventory by tracking stock levels, forecasting future demand based on past sales data, and optimizing reorder quantities.
### Key Features
Load Inventory Data: Reads inventory details from a CSV file.
Inventory Management: Generates alerts if stock falls below reorder levels or exceeds maximum limits.
Demand Forecasting: Predicts product demand using a simple moving average based on past sales.
Supply Optimization: Suggests reorder quantities to maintain optimal stock levels.
### Project Structure
├── inventory_forecasting_notebook.ipynb    # Jupyter Notebook with code and explanations

├── inventory_data.csv                       # Sample inventory data file
 
├── main.py                                  # Python script version of the project

├── README.md                                # Project documentation

### How to Use
Clone this repository.
Install dependencies: pip install pandas numpy
Run the Jupyter notebook or Python script:
python main.py
Enter the path to your inventory CSV file when prompted.
### Example Output
ALERT: Laptop is below reorder level!

Demand Forecast for Next 3 Months:
Laptop: [50.0, 50.0, 50.0]

Reorder Suggestions:
Laptop: Reorder 100 units
