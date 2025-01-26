# Zomato Data Analysis Project

## Project Overview

This project involves analyzing Zomato restaurant data to gain insights into various aspects of restaurant operations, such as ratings, order preferences, and customer voting trends. By leveraging Python libraries like Pandas, NumPy, Matplotlib, and Seaborn, the dataset was explored to extract meaningful conclusions.

## Dataset

The dataset contains information about 148 restaurants with the following columns:

- **name**: Name of the restaurant
- **online\_order**: Indicates whether the restaurant accepts online orders (Yes/No)
- **book\_table**: Indicates whether table booking is available (Yes/No)
- **rate**: Customer rating (e.g., 4.1/5)
- **votes**: Number of customer votes
- **approx\_cost(for two people)**: Approximate cost for two people
- **listed\_in(type)**: Type of restaurant (e.g., Buffet, Dining)

## Key Steps and Insights

### 1. Data Preprocessing

- The **rate** column was cleaned by converting values from strings (e.g., '4.1/5') to floats.
- The dataset was checked for null values and appropriate data types were assigned to each column.

### 2. Visualizations and Analysis

#### Type of Restaurants

- A count plot showed the distribution of restaurant types. **Conclusion:** The majority of restaurants fall under the "Dining" category.

#### Votes by Restaurant Type

- A grouped bar chart displayed total votes per restaurant type. **Conclusion:** Dining restaurants received the maximum votes.

#### Rating Distribution

- A histogram was created to display the distribution of restaurant ratings. **Conclusion:** Most restaurants received ratings between 3.5 and 4.

#### Spending Trends

- A count plot highlighted the most common cost ranges for couples. **Conclusion:** Most couples prefer restaurants with an approximate cost of 300 Rs.

#### Online vs. Offline Ratings

- A box plot was used to compare ratings for restaurants that accept online orders versus offline. **Conclusion:** Restaurants accepting online orders received higher ratings than those that don't.

#### Heatmap of Order Modes

- A pivot table and heatmap analyzed the distribution of online and offline orders across restaurant types. **Conclusion:** Dining restaurants primarily receive offline orders, whereas cafes are preferred for online orders.

## Libraries Used

- **Pandas**: Data manipulation and preprocessing
- **NumPy**: Numerical operations
- **Matplotlib**: Data visualization
- **Seaborn**: Advanced visualization

## Conclusions

- Dining restaurants dominate both in popularity and customer votes.
- Online ordering significantly boosts ratings compared to offline services.
- Customers tend to prefer low-cost dining options, with 300 Rs being the most popular range.
- Restaurants and cafes have distinct order preferences based on customer behavior.

## Future Scope

- Analyze customer feedback and review texts to understand preferences.
- Incorporate additional datasets like location and cuisine type for more granular insights.

---





