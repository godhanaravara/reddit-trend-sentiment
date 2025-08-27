# Reddit AI Job Sentiment Tracker (2025)

![Wordcloud](images/ai_terms.png)  
*A visualization of emerging negative terms in AI job discourse*

---

## ▸ Project Overview
Artificial Intelligence is reshaping the job market with sparking **optimism, skepticism, and fear** across online communities.  
This project dives into **Reddit discussions** to uncover public sentiment around AI and employment in 2025.

Using **NLP + Visualization**, I track sentiment trends across subreddits, surface emerging themes, and visualize how people really feel about AI’s impact on jobs.

---

## ▸ The Challenge
The [World Economic Forum](https://www.weforum.org/publications/the-future-of-jobs-report-2025/digest/) forecasts that **slower growth could displace 1.6 million jobs globally by 2030**. At the same time, although no study explicitly quantifies public relations (PR) damages in the AI sentiment arena, analogous cases, such as sudden viral backlash or failure to respond to public concerns, are widely understood in marketing and communications to risk costs in the **hundreds of thousands of dollars**.  

Together, these trends highlight the need for **real-time insights into how AI is perceived in the workforce**, so organizations can adapt early and avoid reputational or financial fallout.

---

## ▸ The Solution

I built this tracker to turn raw Reddit data into actionable intelligence. Here’s how it works:  

✦ Fetches over 2,000 real-time posts from "artificial" and "future" subreddits.  
✦ Filters for AI job topics like "automation" and "2025" using natural language processing.  
✦ Analyzes sentiment with VADER, ranging from -1 to 1, to gauge public mood.  
✦ Visualizes trends with Plotly charts and word clouds, highlighting key concerns.  
✦ Predicts viral potential with a Gradient Boosted Tree model.  


---

## ▸ Getting Started
Ready to explore? Follow these steps to run the project:
- Clone the repository: `git clone https://github.com/godhanaravara/reddit-trend-sentiment.git`
- Install dependencies: `pip install -r requirements.txt`
- Create a `.env` file with your Reddit API credentials:

```python
CLIENT_ID=your_client_id_here  
CLIENT_SECRET=your_client_secret_here  
USER_AGENT=SentimentTracker_v0.1_by_u_godhanaravara  
```

- Add `.env` to `.gitignore` to keep it secure.
- Open `RedditSentiment.ipynb` in Databricks or a local Jupyter environment.

---

## ▸ Key Insights
- Filtered 85 posts from 1,489, with sentiment scores ranging from -0.7405 to 0.9626, indicating a mix of perspectives, with a notable high of 0.9626 observed on August 27, 2025.
- Word clouds highlight negative terms such as "layoff," "automation," and "displacement," reflecting key concerns in AI job discourse.
- Daily sentiment trends exhibit fluctuations, providing a dynamic view of evolving opinions and enabling timely business responses.

Check out the visualizations in `RedditSentiment.ipynb`!

---

## ▸ Tech Stack
This project leverages:

- ![Databricks](https://img.shields.io/badge/Databricks-EC6B24?style=for-the-badge&logo=databricks&logoColor=white) + ![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white): For scalable data processing, serving as the primary development and execution environment.
- ![PySpark](https://img.shields.io/badge/PySpark-FF5722?style=for-the-badge&logo=apachespark&logoColor=white): For advanced data transformation and DataFrame operations.
- ![PRAW](https://img.shields.io/badge/PRAW-2196F3?style=for-the-badge&logo=python&logoColor=white): To pull real-time Reddit data.
- ![NLP](https://img.shields.io/badge/NLP-9C27B0?style=for-the-badge&logo=natural-language-processing&logoColor=white): For natural language processing to clean, filter, and analyze text data.
- ![NLTK](https://img.shields.io/badge/NLTK-4CAF50?style=for-the-badge&logo=python&logoColor=white) + ![VADER](https://img.shields.io/badge/VADER-8BC34A?style=for-the-badge&logo=python&logoColor=white): Supporting tools for NLP, used for text cleaning and sentiment analysis.
- ![Plotly](https://img.shields.io/badge/Plotly-3F51B5?style=for-the-badge&logo=plotly&logoColor=white) + ![Matplotlib](https://img.shields.io/badge/Matplotlib-F44336?style=for-the-badge&logo=matplotlib&logoColor=white): For dynamic and static visualizations.
- ![XGBoost](https://img.shields.io/badge/XGBoost-673AB7?style=for-the-badge&logo=xgboost&logoColor=white): For predicting viral post potential.
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white): The core language for coding and integration.
- ![re (Regular Expressions)](https://img.shields.io/badge/re-9E9E9E?style=for-the-badge&logo=python&logoColor=white) (Regular Expressions): For text processing.
- ![Git](https://img.shields.io/badge/Git-F44336?style=for-the-badge&logo=git&logoColor=white) + ![GitHub](https://img.shields.io/badge/GitHub-212121?style=for-the-badge&logo=github&logoColor=white): For version control and project hosting.
- ![dotenv (python-dotenv)](https://img.shields.io/badge/dotenv-607D8B?style=for-the-badge&logo=python&logoColor=white): For secure environment variable management.
- ![Databricks Notebook](https://img.shields.io/badge/Databricks_Notebook-EC6B24?style=for-the-badge&logo=databricks&logoColor=white): The interactive development interface for writing, testing, and documenting the project.

---

## ▸ About Me
I am a data enthusiast passionate about using AI to understand human trends. This project reflects my journey in blending technology with real-world impact. Connect with me on [LinkedIn](https://www.linkedin.com/in/yourprofile) or explore more at my [GitHub](https://github.com/godhanaravara)!


