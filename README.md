# Superstore Sales Analysis - Exploratory Data Analysis (EDA)

## Overview
This project is an exploratory data analysis (EDA) of a Superstore dataset, focusing on sales, profit, and customer behavior. The analysis aims to uncover key insights that can help optimize business strategies, improve profitability, and enhance customer satisfaction.

## Dataset
The dataset contains 9,994 records with 21 columns, including:
- Order and shipping details (`Order ID`, `Order Date`, `Ship Date`, `Ship Mode`)
- Customer information (`Customer ID`, `Customer Name`, `Segment`, `Country`, `City`, `State`, `Postal Code`, `Region`)
- Product details (`Product ID`, `Category`, `Sub-Category`, `Product Name`)
- Sales metrics (`Sales`, `Quantity`, `Discount`, `Profit`)

## Key Questions Explored
1. **Top Selling Products**: Identified the top 5 products by sales.
2. **Sales Trends**: Analyzed monthly and yearly sales trends.
3. **Revenue by Category**: Compared revenue (Sales + Profit) across product categories.
4. **Regional Sales Performance**: Determined which region generates the most sales.
5. **Impact of Discounts**: Examined how discounts affect sales volume.
6. **Profit Margins**: Calculated average profit margins for each product category.
7. **Sub-Category Demand**: Identified the most demanded sub-categories.

## Key Findings
1. **Top Selling Products**:
   - The "Canon imageCLASS 2200 Advanced Copier" generated the highest sales ($61,599.82).
   - Other top products include "Fellowes PB500 Electric Punch Plastic Comb Binding Machine" and "Cisco TelePresence System EX90 Videoconferencing Unit."
-----------------------------------------------------------------------------------------------------------------------------------------------------------     
![Screenshot 2025-03-31 170531](https://github.com/user-attachments/assets/7eb55d54-b299-49e6-b2f2-8c1b9a81aa1b)


2. **Sales Trends**:
   - Sales peaked in November and December, likely due to holiday shopping.
   - Year-over-year growth was observed, with 2017 showing the highest sales.
![newplot](https://github.com/user-attachments/assets/88b84782-0bce-40ac-9e58-f847d74b31fa)


3. **Revenue by Category**:
   - Technology contributed the most to total revenue ($1,058,768.82), followed by Office Supplies ($954,768.35) and Furniture ($882,323.29).
![newplot2](https://github.com/user-attachments/assets/064fcc2e-8701-4f51-950d-f3147fae7000)


4. **Regional Sales Performance**:
   - The West region had the highest sales ($725,457.82), followed by the East ($678,781.24).
![newplot3](https://github.com/user-attachments/assets/699405fb-5fd7-482c-a896-7c563331f635)


5. **Impact of Discounts**:
   - Discounts of 20% were most common and led to higher sales volumes.
   - However, excessive discounts (e.g., 80%) did not significantly boost sales.
![newplot4](https://github.com/user-attachments/assets/c458f719-e359-46fb-b3dc-e33a36572638)


6. **Profit Margins**:
   - Office Supplies had the highest average profit margin (42.64%), while Technology had the lowest (22.87%).
![newplot5](https://github.com/user-attachments/assets/e467261a-a0e4-4cc8-8a57-38cc7d266f92)


7. **Sub-Category Demand**:
   - "Binders" and "Paper" were the most demanded sub-categories, with 5,974 and 5,178 units sold, respectively.
![newplot6](https://github.com/user-attachments/assets/d932b383-ca2a-4d8f-9e71-36f6d6b2ea58)


## Tools Used
- **Python Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical operations.
  - `matplotlib` and `seaborn` for basic visualizations.
  - `plotly` for interactive visualizations.
- **Visualization**:
  - Interactive charts (line plots, bar charts, pie charts, scatter plots) to highlight trends and comparisons.

## How to Run the Code
1. Ensure you have Python installed (version 3.6 or higher).
2. Install the required libraries:
   ```
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Download the dataset and update the file path in the notebook.
4. Run the Jupyter notebook `Store_EDA.ipynb` to reproduce the analysis.

## Future Work
- Incorporate customer segmentation analysis to identify high-value customers.
- Explore the relationship between shipping modes and customer satisfaction.
- Predict future sales using time-series forecasting models.

## Author
Josam Hany Fouad 
[My LinkedIn Profile.](https://www.linkedin.com/in/josam-hany-76b449301/)
[The Project Post.](https://www.linkedin.com/posts/josam-hany-76b449301_datascience-eda-python-activity-7312491519213481984-9KrL?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE0hRQMBJwwXzE_2WIlbIlC2-W8nTypJdkU)  
## DataSet
You can find this dataset on kaggle [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/data)
## License
This project is open-source and available under the [MIT License](LICENSE).
