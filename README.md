# Why People Quit: Multi-Modal Data Mining Project

This project explores the emotional, thematic, and visual factors that influence why individuals leave their jobs. We use both structured datasets (IBM HR Analytics, City of Austin Employees) and unstructured data to analyze patterns. Our approach combines natural language processing, machine learning, and computer vision techniques to uncover key insights.

---

## Project Structure

- **Structured Data Analysis**
  - IBM HR Analytics Employee Attrition Dataset
  - City of Austin Employee Dataset
  - Preprocessing, statistical analysis, and attrition factor exploration
  
- **Unstructured Data Analysis**
  - Reddit comment mining from career-related threads
  - Sentiment analysis using VADER and BERT
  - TF-IDF keyword extraction to surface dominant themes
  - Model comparison between rule-based and transformer-based sentiment detectors

- **Visual Data Analysis**
  - Frame extraction from workplace-related videos
  - Feature extraction using CNN (Convolutional Neural Networks)
  - Brightness-based K-means clustering to detect emotional tone shifts in video content

- **Visualization Outputs**
  - Sentiment distribution charts comparing VADER and BERT
  - Top TF-IDF term rankings
  - Brightness segmentation clusters from video frames

---

## Datasets Used

- **IBM HR Analytics Employee Attrition Dataset**  
  Public dataset containing HR data and employee turnover information.  
  [View Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

- **City of Austin Employee Dataset**  
  Public dataset listing compensation and employment information for City of Austin employees.  
  [View Dataset](https://data.austintexas.gov/City-Government/City-Employee-Compensation/5fmi-ynp3)

- **Reddit Career Discussions Dataset**  
  A manually mined set of Reddit posts and comments discussing reasons for quitting jobs, scraped from multiple career-related subreddits.
  
---

## Project Highlights

- **Structured Insights**: Statistical analysis on HR datasets helped identify traditional drivers of attrition such as overtime rates, job satisfaction, and salary disparities.

- **Unstructured Sentiment Mining**: By comparing VADER and BERT, we demonstrated how language model choice can dramatically alter the perceived sentiment in user-generated career discussions.

- **Visual Emotional Mapping**: CNN-based clustering of video brightness revealed tonal shifts that correlate with emotional intensity, supplementing textual data.

- **End-to-End Pipeline**: From data gathering to model evaluation and final visualization, this project presents a comprehensive, multi-modal perspective on attrition.

---

## Team

- **Tyler Gannon** 
- **Adriana Cruz** 
- **Chad Trudgeon**
- **Andrew Herbert**

---

## Conclusion

This project merges structured HR datasets, unstructured career discussions, and visual emotional patterns into a unified, data-driven narrative explaining why people leave their jobs. By blending classic statistical analysis, modern natural language processing, and deep learning-based vision techniques, we create a richer and more holistic understanding of quitting behavior.


[Read the full blog post here.](https://medium.com/@thetylergannon/63c057eaf55f)

---
