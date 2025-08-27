# Reddit AI Job Sentiment Tracker (2025)

![Wordcloud](images/ai_terms.png)  
*A visualization of emerging negative terms in AI job discourse*

---

## Project Overview
Artificial Intelligence is reshaping the job market with sparking **optimism, skepticism, and fear** across online communities.  
This project dives into **Reddit discussions** to uncover public sentiment around AI and employment in 2025.

Using **NLP + Visualization**, I track sentiment trends across subreddits, surface emerging themes, and visualize how people really feel about AI’s impact on jobs.

---

## The Challenge
In 2025, tech firms face a pressing issue: losing over $500,000 in PR costs when they miss viral shifts in public opinion, like the World Economic Forum's forecast of 1.6 million job displacements. Staying ahead requires real-time insights into how AI is perceived in the workforce.

---

## The Solution
I built this tracker to turn raw Reddit data into actionable intelligence. Here’s how it works:
✦ Fetches over 1,000 real-time posts from "artificial" and "futurology" subreddits.
✦ Filters for AI job topics like "automation" and "2025" using natural language processing.
✦ Analyzes sentiment with VADER, ranging from -1 to 1, to gauge public mood.
✦ Visualizes trends with Plotly charts and word clouds, highlighting key concerns.
✦ Predicts viral potential with a Gradient Boosted Tree model.

---

## Getting Started
Ready to explore? Follow these steps to run the project:
- Clone the repository: `git clone https://github.com/godhanaravara/Reddit-AI-Job-Sentiment-Tracker-2025.git`
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

## Key Insights
- Filtered 131 posts from 1,110, with positive sentiment dominating (e.g., 0.9626 on July 14, 2025).
- Word clouds reveal negative terms like "layoff" and "automation".
- Daily sentiment trends show fluctuations, offering a window into evolving opinions.

Check out the visualizations in `RedditSentiment.ipynb`!

---

## Tech Stack
This project leverages:
- **Databricks + Spark**: For scalable data processing.
- **PRAW**: To pull real-time Reddit data.
- **NLTK + VADER**: For text cleaning and sentiment analysis.
- **Plotly + Matplotlib**: For dynamic and static visualizations.
- **XGBoost**: For predicting viral post potential.

---

## License
MIT License - feel free to use with credit, but please avoid commercial use without permission.

---

## About Me
I am a data enthusiast passionate about using AI to understand human trends. This project reflects my journey in blending technology with real-world impact. Connect with me on [LinkedIn](https://www.linkedin.com/in/yourprofile) or explore more at my [GitHub](https://github.com/godhanaravara)!

