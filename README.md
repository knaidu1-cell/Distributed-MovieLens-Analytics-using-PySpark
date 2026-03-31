PySpark MovieLens Analysis Project

Project Overview
This project demonstrates how to leverage Apache PySpark for scalable data processing and analysis on the large-scale MovieLens 20M dataset, illustrating a real-world data analytics workflow. The primary objective is to extract meaningful business and analytical insights from user movie rating data with distributed computing and present the results through professional, static visualizations suited for BI or decision-making audiences.

 gained hands-on experience in:

Ingesting and preprocessing big datasets at scale using PySpark DataFrames and SQL

Computing significant analytical insights on user preferences and movie popularity

Designing clear and informative static plots using matplotlib/seaborn for effective storytelling of results

Bridging big data processing with impactful communication to technical and non-technical stakeholders

Top 10 Highest Rated Movies
Objective: Identify the movies with the highest average user ratings to understand viewer preferences.
Business Value: Helps streaming platforms tailor recommendations and content acquisition strategies.

Top 10 Most Active Users by Number of Ratings
Objective: Determine highly engaged users by counting their submitted ratings.
Analytical Value: Identifies power users for targeted marketing or engagement campaigns.

Distribution of Movie Ratings
Objective: Analyze the overall distribution of ratings to explore user rating patterns and potential biases.
Business Relevance: Provides context for algorithm tuning and bias mitigation in recommendation engines.

Each insight is accompanied by well-crafted static visualizations with descriptive titles, legends, and captions, created post-PySpark processing via conversion to Pandas where necessary.

Project Structure
Pyspark-1.ipynb: Main PySpark notebook containing data loading, cleaning, analysis, and plotting

plots/: Directory where generated PNG static plots are saved

README.md: This project overview and instructions

Technologies Used
Apache Spark (PySpark) for distributed data processing and SQL analysis

Python pandas for small data manipulations and plotting

Matplotlib and Seaborn for static, publication-quality visualizations

Jupyter Notebook for interactive execution and presentation

Conclusion
This project bridges the gap between big data analytics and business storytelling by using PySpark to scale computations and creating clear visual insights that are easily interpretable by business users and decision makers. It serves as a practical example of real-world data workflows in the BI and data science industry, expanding your capabilities in scalable data wrangling, analysis, and communication.
