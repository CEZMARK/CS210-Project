YouTube Viewing History Analysis
Overview
This project involves a comprehensive analysis of my personal YouTube viewing history. It aims to uncover insights into my content preferences, viewing habits, and trends over time. The data was obtained directly from Google and encompasses a range of information including video titles, channel names, and viewing timestamps.

Data Source
The data was acquired through Google's data takeout service. It includes an extensive history of videos watched on YouTube, providing a rich dataset for analysis.

Methodology
The analysis process involved several key steps:

Data Extraction: Using BeautifulSoup to parse HTML data.
Data Transformation: Converting extracted data into a structured pandas DataFrame.
Feature Engineering: Extracting additional features like view time, day of the week, and month.
Exploratory Data Analysis: Conducting preliminary analysis using pandas and custom summary functions.
Visualization: Creating visual representations of the data using seaborn and matplotlib.
Key Findings
Dominant content preferences and frequently watched channels.
Specific patterns in viewing times, suggesting preferred periods for YouTube consumption.
Evolution of interests over time, based on changes in viewing patterns.
Limitations
Limited metadata, focusing primarily on titles and timestamps.
Subjectivity in the categorization of content.
Absence of comparative analysis with broader user data.
Future Work
Implement machine learning for sentiment analysis and content categorization.
Develop an interactive dashboard for real-time data exploration.
Extend the analysis scope to include cross-platform data.
How to Use
Data Collection: Request your YouTube viewing history from Google's data takeout service.
Running the Analysis: Use the provided Jupyter notebook (youtube-viewing-history-analysis.ipynb) to perform the analysis. Ensure you have the necessary libraries installed (pandas, BeautifulSoup, seaborn, matplotlib).
Viewing the Results: Explore the visualizations and insights generated in the notebook.
Contributing
Contributions to the project are welcome. Please adhere to the project's code of conduct and follow the standard fork-pull request workflow.

License
This project is open-sourced under the MIT License.
