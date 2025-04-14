# Russia-Ukraine War Sentiment Analysis with DistilBERT

This project explores public sentiment surrounding the Russia-Ukraine war using Twitter data collected during the early months of 2022. The goal is to analyze how sentiment evolved over time and gain insight into public discourse during a critical global event.

### What I Did

- Collected and cleaned tweet data related to the Russia-Ukraine conflict.
- Applied **DistilBERT**, a state-of-the-art transformer model from Hugging Face, to perform sentiment analysis.
- Visualized sentiment trends over time to understand how public opinion shifted.
- Organized the project using Git and GitHub to demonstrate my skills in machine learning and software development best practices.

---

## Dataset

The dataset was sourced from Kaggle and consists of tweets containing keywords like "ukraine war", "russian troops", and "NATO", collected between **January 1, 2022** and **March 6, 2022**.

- 🔗 [Kaggle Dataset](https://www.kaggle.com/datasets/foklacu/ukraine-war-tweets-dataset-65-days)
- Format: Multiple `.csv` files with tweet text and metadata.

---

## Sentiment Analysis

- I used the **DistilBERT** model fine-tuned for sentiment classification, available on Hugging Face.
- The Hugging Face sentiment analysis pipeline helped me quickly get results with minimal setup.
- 🔗 [Hugging Face Blog: Sentiment Analysis with Python](https://huggingface.co/blog/sentiment-analysis-python)

### Tools & Libraries:
- `transformers` (Hugging Face)
- `pandas`, `matplotlib`, `seaborn`
- `scikit-learn` for any preprocessing or metrics

---

## Visualizations

In the final stage of the analysis, I created visualizations to show how sentiment (positive/negative) fluctuated over time. These visualizations help tell a compelling story about how global conversations evolved during the early phase of the war.

Sample plot included:
- Stacked bar chart of tweet sentiment by date
- Pie Charts differentiated by country mentioned in tweet

---
