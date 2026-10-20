Social Media Engagement Analysis
Project Overview
This project analyzes social media engagement data using Python. It
covers data cleaning, exploratory data analysis, feature engineering,
statistical analysis, and visualization to explore how content type,
category, audience characteristics, sentiment, country, and device
relate to engagement.
Dataset
- File: social_media_engagement_5000.csv
- Data loaded with: Pandas read_csv()
- The notebook uses fields such as likes, comments, shares,
  posted_at, post_type, post_category, country, gender,
  age, engagement_rate, follower_count, impression_count,
  watch_time_sec, sentiment, device_type, and is_verified.
Place the CSV file in your project folder and update the file path in
the notebook if needed. The original notebook uses a local Windows
file path.

Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
Project Workflow
1. Data Import and Setup
- Imported the dataset using Pandas.
- Checked dataset structure and data types.
- Converted the posted_at column to datetime.
- Converted a column to a NumPy array and calculated the mean of
  comments.
2. Data Cleaning
- Checked missing values.
- Filled numeric missing values using median imputation.
- Forward-filled date values and handled missing gender and sentiment
  values.
- Checked for duplicate rows.
- Standardized text formatting and cleaned column names.
3. Exploratory Data Analysis
- Examined the first and last rows, dataset shape, columns, and data
  types.
- Generated descriptive statistics.
- Explored categorical distributions and unique values.
- Created a numeric correlation matrix.
- Compared average likes and shares by post type.
4. Data Wrangling and Feature Engineering
- Practiced concatenating DataFrames.
- Created engagement_score by adding likes, comments, and shares.
- Created hashtag_counts by counting hashtags in the hashtags
  column.
- Grouped data by post type, country, and sentiment to calculate
  average likes, total shares, and post counts.
5. Statistical Analysis
Calculated summary statistics for likes, comments, shares, watch time,
engagement rate, and follower count, including: - Mean, median, and
mode - Descriptive statistics and percentiles - Variance - Skewness and
kurtosis
6. Data Visualization
The notebook includes visualizations such as: - Scatter plot: likes
vs. impressions - Line chart: daily engagement trend - Bar chart: number
of posts by category - Pie chart: gender distribution - Histogram: user
age distribution - Correlation heatmap - Count plot: post type - Violin
plot: follower count by sentiment - Interactive Plotly scatter plot:
impressions vs. likes by post type
Key Insights Recorded in the Notebook
- Post type: Video posts had the highest average engagement rate
  in the notebook's results, followed by text posts.
- Content category: Food was recorded as the highest-performing
  category by average engagement rate.
- Country: Brazil had the highest average engagement rate among
  the countries compared.
- Age: The notebook reports engagement peaks around age 24 and
  within the 50--55 age range.
- Account verification: Verified accounts had a slightly higher
  average engagement rate than unverified accounts.
- Device type: Mobile users had the highest average watch time.
- Sentiment: The notebook notes differences in engagement across
  sentiment categories; neutral posts were reported as having the
  highest average engagement in one summary.
These findings reflect the calculations and written notes in the
notebook. Re-run the notebook against the final dataset to confirm the
values.
Skills Demonstrated
Python, Pandas, NumPy, data cleaning, missing-value handling,
exploratory data analysis (EDA), feature engineering, grouping and
aggregation, descriptive statistics, data visualization, Matplotlib,
Seaborn, and Plotly.
