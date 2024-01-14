# Content Performance Visualization Project
This project involves the analysis and visualization of content performance for various categories over time. The primary goal is to explore the audience engagement trends by plotting the sum of scores for the top 5 categories on a daily basis.

# Project Structure

# 1. Data Preprocessing:
The project begins by loading the dataset containing information about content categories, scores, and timestamps.
The 'Datetime' column is converted to the datetime data type to facilitate time-based operations.

# 2. Grouping and Aggregation:
The data is then grouped by 'Category' and 'Datetime,' and the sum of scores is calculated for each day.

# 3. Top Performing Categories:
The top 5 performing categories are identified based on the sum of scores.

# 4. Plotting:
Utilizing Plotly Express, an interactive bar chart is generated to visualize the daily performance of the top 5 categories.
Each bar represents the sum of scores for a specific day, with different categories distinguished by color.
