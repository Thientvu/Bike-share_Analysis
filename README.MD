### Cyclistic Bike-share Case Study: Navigating Speedy Success

#### Project Overview
This case study aims to analyze the usage patterns of Cyclistic's bike-share system between annual members and casual riders. The focus is on understanding these different user behaviors to guide future marketing strategies.

#### Data and Tools
- **Data Source**: Structured dataset from Divvy Bikes spanning 12 months of 2022, hosted on Amazon AWS S3, containing details such as ride types, start and end times, and station information.
- **Technologies Used**: Python (pandas, numpy, seaborn, matplotlib), Tableau for visualization, and SQLite for data management.
- **Data Integrity**: The dataset required significant cleaning due to issues like missing values and inaccurate timestamps, which was handled using Python.

#### Key Insights
- **Usage Patterns**: Casual riders generally have longer ride durations than annual members, contrary to the assumption that members would use the service more intensively.
- **Bike Preferences**: Casual riders prefer electric bikes and exhibit the longest rides on docked bikes, while members prefer classic bikes and show consistent usage patterns throughout the week.
- **Spatial and Temporal Trends**: Key stations like Streeter Dr & Grand Ave are hotspots for casual riders, especially on weekends. Casual riders' maximum ride lengths peak in January, March, and July.

#### Analytical Process
- Data was cleaned and merged into a single DataFrame, with time data parsed for accurate analysis.
- Missing data points were either imputed or dropped based on their impact on the overall dataset integrity.
- Analysis focused on ride durations, bike preferences, and usage frequency by day and station.

#### Conclusion
The findings challenge some existing assumptions about member usage and highlight opportunities for targeted marketing to convert casual riders into annual members.

#### Repository Contents
- **Analysis Notebooks**: Python scripts used for data cleaning, analysis, and visualizations.

#### How to Use This Repository
Clone or download the repository to access the Python notebooks and datasets, and replicate or extend the analysis.

#### Resources
- [Data License Agreement](https://divvybikes.com/data-license-agreement)

For detailed insights and further discussion, refer to the linked resources or contact me through the repository's Issues section.
