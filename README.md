# Reddit Comment Engagement Analysis
This project explores the factors influencing engagement on Reddit comments using **web scraping and regression analysis**. The dataset is collected via the **Reddit API (PRAW)** and includes features like sentiment, text structure, posting time, and user metadata. We aim to identify key drivers of engagement (comment score and replies) through regression modeling.

## Dataset Overview
### **Who, What, When, Where, and How the Data Was Collected**
- **Who:** Comments from users posting in selected subreddits.
- **What:** Extracted metadata and text-based features, including:
  - Engagement metrics (comment score, number of replies).
  - Sentiment analysis scores.
  - Structural features (word count, text length, question/emoji presence).
  - Metadata (posting time, comment age, user karma, account age).
- **When:** Data is scraped **live** when the script is run.
- **Where:** Reddit (using the [PRAW API](https://praw.readthedocs.io/en/stable/)).
- **How:** Python script fetches **top 10 posts** (adjustable), extracts comments, processes text features (via **VADER for sentiment, SpaCy for NLP, better_profanity for filtering**), and stores the dataset in CSV format.

---

## Statistical Description of the Dataset
- **Data Types & Structure**:
  - The dataset consists of **16 features** (including numerical, categorical, and binary variables).
  - **Continuous variables:** Sentiment score, comment score, text length, word count, user karma, account age, comment age.
  - **Categorical variables:** Subreddit name, comment hour, comment day.
  - **Binary variables:** Contains emoji, contains question, contains profanity, is early comment.

## Proposal Writing Guidelines
- The **proposal is limited to 2 pages** (font size **10**).
- It must be submitted in **PDF format** along with a sample dataset.
- The proposal must include:
  1. **Dataset Description** (data structure, types, and distributions).
  2. **Data Collection Process** (who, what, when, where, how).
  3. **Scientific Hypotheses** (questions to be explored).
  4. **Challenges & Limitations** (potential biases, data access restrictions, API rate limits).
- **EDA (Optional but Encouraged):** Group members are encouraged to **visualize distributions (histograms, boxplots), detect outliers, and compute correlations**.

## Possible Scientific Questions to Investigate
1. **What factors predict Reddit comment engagement?**
2. **How do metadata features influence engagement?** 

---
