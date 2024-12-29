# dsa210_project
# YouTube Watching Pattern Analysis

## Project Description
This project explores the relationship between my YouTube viewing patterns and meal times. The analysis investigates whether my YouTube watching habits align with food ordering times, based on payments made to Yemeksepeti, a food delivery service. The hypothesis is that YouTube watching times are correlated with eating times, potentially revealing insights about consumption habits during meals.

By integrating two datasets—YouTube viewing history and a mock bank account transactions database—the project aims to uncover correlations between digital media consumption and daily routines.

---

## Dataset Description
1. YouTube Viewing History

This dataset was exported via Google Takeout and contains:

Timestamp: Exact date and time of video views.

Video Titles: Descriptions of the content watched.

Video URLs: Links for further exploration.

Channels: Content creators associated with the videos.

Metadata: Additional information like watch settings and history status.

2. Bank Account Transactions Database

This dataset shows payments made to Yemeksepeti, indicating food orders. The features include:

Transaction ID: Unique identifier for each transaction.

Timestamp: Date and time of the payment.

Amount: Payment value in Turkish Lira (TRY).

Merchant Name: Confirmed as "Yemeksepeti."

The purpose of this data is to approximate meal times based on food delivery records and correlate these with YouTube viewing sessions.

---

## Project Goals
The main objectives of this project are:

1. **Exploring Viewing Patterns**:
   - Determine the hours during which I am most active on YouTube.
   - Compare hourly viewing habits to identify differences in behavior.

2. **Uncovering Behavioral Insights**:
   - Correlate viewing times with daily meals.
   - Analyze how habits evolve over time, identifying potential triggers or patterns.

3. **Creating Visualizations**:
   - Generate visually compelling representations of viewing trends, such as heatmaps and line graphs, to make the insights intuitive and actionable.

4. **Documenting Key Findings**:
   - Summarize the results of the analysis to draw meaningful conclusions.
   - Highlight any surprising or unexpected patterns in my watching history.

5. **Laying the Foundation for Future Analysis**:
   - Suggest additional avenues for exploration, such as analyzing content genres or combining YouTube data with other activity logs for a holistic view of my habits.

---

## Planned Steps
To achieve the project goals, the following steps will be undertaken:

1. **Data Cleaning and Preprocessing**:
   - Convert timestamps from UTC to local time for accurate interpretation.
   - Extract key fields, such as date, time, and video details, into a structured format like CSV for easier manipulation.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze the frequency of viewing by hour.
   - Summarize total time spent watching videos and categorize habits into morning, afternoon, evening, or late-night.
  
3. **Merging Datasets**:

   -Join the YouTube and transaction datasets based on timestamps.
   -Create derived features, such as time gaps between transactions and viewing activities.

3. **Visualization**:
   - Create detailed heatmaps to visualize hourly activity patterns.
   - Use time-series graphs to illustrate changes in habits over time.
   - Compare viewing behavior on workdays versus weekends using bar charts.

4. **Insights and Documentation**:
   - Identify correlations, such as increased activity during specific times of the day.
   - Present findings in a clear, actionable format with accompanying visuals.

5. **Future Work and Recommendations**:
   - Explore deeper insights by analyzing content genres or viewing duration.
   - Suggest changes to improve productivity or reduce potential overuse of YouTube.

---

## Tools and Libraries
The project will utilize the following tools and libraries:

- **Python**: The primary programming language for data processing and analysis.
- **Pandas**: For cleaning, filtering, and structuring the data.
- **Matplotlib and Seaborn**: To create static and interactive visualizations.
- **NumPy**: For mathematical computations where needed.
- **Google Takeout**: To export and download YouTube activity data.

These tools ensure efficient data handling and insightful analysis.

---

## Acknowledgments
I extend my gratitude to Google Takeout for providing access to my YouTube watch history data. This project is a testament to how personal data can offer valuable insights when analyzed thoughtfully.

