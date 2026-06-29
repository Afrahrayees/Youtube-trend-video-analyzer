📊 YouTube Trend and Video Analyzer

* Overview

This project started as a personal tool to analyze my own YouTube channel. As a content creator, I wanted to better understand what makes videos perform well and use those insights to improve future content. Over time, I expanded it into a complete data analysis project that combines YouTube Analytics data with real-time trends collected using the YouTube Data API.

The project uses Python for data cleaning, analysis, visualization, and a rule-based scoring system that predicts how well a future video idea aligns with patterns found in high-performing videos.

---

* Setup

1. Install the required packages:

```bash
pip install -r requirements.txt
```

2. Create a YouTube Data API v3 key from Google Cloud Console.

3. Replace the placeholder API key in the notebook with your own before running the project.
 

Features

* Analyse YouTube Analytics export data
* Clean and pre-process video performance data
* Create a composite performance score
* Classify videos into High, Medium, and Low performance groups
* Extract common keywords from successful video titles
* Analyse video duration and audience retention
* Visualize relationships between performance metrics
* Collect real-time trending art videos using the YouTube Data API
* Filter genuine art-related content
* Rank high-performing videos based on engagement


---

 Technologies Used

* Python
* Pandas
* Matplotlib
* Google Colab
* YouTube Data API v3

---

 Dataset

The original YouTube Studio Analytics dataset used in this project is not included because it contains personal channel data. The notebook is designed to work with any YouTube Analytics export in the same format.


Project Workflow

1. Load YouTube Analytics data
2. Clean and pre-process the dataset
3. Create a composite performance score
4. Identify high-performing videos
5. Analyse title keywords
6. Study duration and audience retention
7. Build a rule-based scoring engine
8. Visualize performance trends
9. Collect real-time trending videos using the YouTube Data API
10. Filter and rank art-related trending videos


 Example Use Case

Given a video title and duration, the scoring engine evaluates how closely the idea matches characteristics found in successful videos and provides a score with a brief explanation.

---

 Limitations

- The scoring system is rule-based and does not use machine learning.
- The analysis depends on the quality and availability of YouTube Analytics and YouTube Data API data.
- Trend analysis is currently focused on art-related videos.
- The project analyzes only few video data and does not consider thumbnail quality or viewer comments.

Future Improvements

* Train a machine learning model to predict video performance
* Add thumbnail analysis
* Include analysis of comments
* Expand trend analysis across multiple content categories

---

 Author - Afrah Rayees

Built as a personal project to better understand YouTube analytics and content trends while applying Python, data analysis, and API integration to a real-world problem.

