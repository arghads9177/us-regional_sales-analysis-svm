# US Regional Sales Data Analysis and Prediction

## Project Overview

This project focuses on analyzing and predicting sales performance across different regions in the US, based on a comprehensive dataset containing information on various sales channels such as In-Store, Online, Distributor, and Wholesale. With 17,992 rows and 15 columns, the dataset provides insights into sales transactions, customer interactions, and product performance, enabling detailed analysis of sales patterns and trends. The goal of this project is to uncover meaningful insights from the data and build predictive models to forecast prices and optimize sales strategies.

## Dataset Description

The dataset includes detailed information on sales orders, customer interactions, and pricing. Below is a breakdown of the columns in the dataset:

- **OrderNumber**: A unique identifier for each order.
- **Sales Channel**: The channel through which the sale was made (In-Store, Online, Distributor, Wholesale).
- **WarehouseCode**: Code representing the warehouse involved in the order.
- **ProcuredDate**: Date when the products were procured.
- **OrderDate**: Date when the order was placed.
- **ShipDate**: Date when the order was shipped.
- **DeliveryDate**: Date when the order was delivered.
- **SalesTeamID**: Identifier for the sales team involved.
- **CustomerID**: Identifier for the customer.
- **StoreID**: Identifier for the store.
- **ProductID**: Identifier for the product.
- **Order Quantity**: Quantity of products ordered.
- **Discount Applied**: Applied discount for the order.
- **Unit Cost**: Cost of a single unit of the product.
- **Unit Price**: Price at which the product was sold.

This dataset serves as a valuable resource for analyzing sales trends, identifying high-performing products, assessing the effectiveness of different sales channels, and optimizing pricing strategies across various regions.

## Visualization Ideas

1. **Time Series Analysis**: Plot sales trends over time to identify seasonal patterns and changes in demand.
2. **Sales Channel Comparison**: Compare sales performance across different sales channels using bar charts or line graphs.
3. **Product Analysis**: Visualize the distribution of sales across different products using pie charts or bar plots to determine popular products.
4. **Discount Analysis**: Analyze the impact of discounts on sales performance using scatter plots or line graphs.
5. **Regional Performance**: Create geographic maps to visualize sales performance across different regions for better insights into regional trends.

## Data Modelling and Machine Learning Ideas (Price Prediction)

1. **Linear Regression**: Build a linear regression model to predict the unit price based on features such as order quantity, discount applied, and unit cost.
2. **XGBoost Regression**: Use an XGBoost regression model to predict the price, incorporating multiple features and their interactions.
3. **Neural Networks**: Train a neural network to predict unit price, utilizing deep learning techniques to capture complex relationships in the data.
4. **Feature Importance Analysis**: Use tree-based models such as XGBoost or Random Forest to identify the most influential features affecting price prediction.
5. **Time Series Forecasting**: Develop a time series forecasting model to predict future prices based on historical sales data.

These visualizations and models will provide valuable insights into sales patterns and help optimize pricing strategies to improve overall sales performance.

## Project Structure

The project is organized as follows:

- `data/`: Contains the raw dataset.
- `notebooks/`: Jupyter notebooks for data exploration, cleaning, visualization, , model training, and evaluation.
- `models/`: Saved machine learning models.
- `README.md`: Project documentation.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/us-sales-data-analysis.git

## Usage

### Data Exploration and Cleaning

Explore the dataset by performing initial analysis and data cleaning, if necessary. This may involve handling missing values, formatting dates, and checking for outliers.

### Visualizations

Using various visualizations (e.g., time series plots, bar charts, pie charts), analyze sales performance across regions, sales channels, and product types. Gain insights into trends, opportunities, and areas for improvement.

### Predictive Modelling

Train machine learning models, including linear regression, XGBoost, and neural networks, to predict the unit price based on available features. Evaluate model performance using metrics like R², RMSE, and MAE.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or suggestions, feel free to contact the project author at [email2argha@gmail.com].
