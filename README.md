# dsa210_project
# YouTube Watching Pattern Analysis

## Project Description
This project delves into the patterns and trends in my YouTube watching history. By leveraging data exported from Google Takeout, I aim to identify the hours during which I watch videos most frequently and understand behavioral patterns. These may include correlations with daily activities such as watching videos during meals, as part of a work or study break, or just before sleep. Through a structured analysis, the project seeks to offer insights into how digital consumption fits into my everyday life.

This project not only provides a reflection of personal habits but also serves as a foundation for exploring broader behavioral analytics using digital data. Understanding these patterns can shed light on routines and behaviors that might otherwise go unnoticed, offering opportunities for self-awareness and improved time management.

---

## Dataset Description
The dataset used in this project was downloaded from Google Takeout and includes detailed information about my YouTube activity. The data is structured in JSON format, making it suitable for systematic preprocessing and analysis. Key features of the dataset include:

- **Timestamp**: Precise date and time when each video was watched.
- **Video Titles**: The names of the videos, giving context to the type of content viewed.
- **Video URLs**: Links to the watched videos, allowing further exploration if needed.
- **Channels**: Information about the creators or channels behind the videos.
- **Metadata**: Additional activity details, such as watch history settings.

This rich dataset enables comprehensive analysis, from simple time-based trends to more complex behavioral correlations.

---

## Project Goals
The main objectives of this project are:

1. **Exploring Viewing Patterns**:
   - Determine the hours during which I am most active on YouTube.
   - Compare weekday and weekend viewing habits to identify differences in behavior.

2. **Uncovering Behavioral Insights**:
   - Correlate viewing times with daily routines, such as meals or bedtime.
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
   - Analyze the frequency of viewing by hour, day, and week.
   - Summarize total time spent watching videos and categorize habits into morning, afternoon, evening, or late-night.

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

