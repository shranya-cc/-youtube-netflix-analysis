## 💗 YouTube And Netflix Data Analysis Series 💫
An Exploratory, Visual, and Narrative-Driven Analytics Project using Python and it's libraries merged with Public Media Datasets!

## Project Summary 🦋

This project series explores two of the largest global content platforms — **YouTube** and **Netflix** — through the lens of **data-driven storytelling**. It focuses on extracting, cleaning, analyzing, and visualizing media consumption trends using publicly available datasets. 

The objective is to derive **meaningful entertainment insights** while leveraging advanced Python data wrangling and **creative visualization** techniques. Part 3 also introduces **basic sentiment analysis**, voice-to-text conversion, and **visual storytelling using GIFs and animations**.

This project was implemented entirely in **Python (Pandas, Seaborn, Plotly, Matplotlib, and many other libraries)**, is **Google Colab-friendly!**, and includes rich narrative components and a visually compelling output.

---
## Objectives 📌

- Perform **exploratory data analysis (EDA)** on YouTube trending videos and Netflix content  
- Uncover genre, sentiment, polarity and viewership trends across regions and time  
- Build storytelling-oriented visualizations with Sankey, Chord, and animated charts  
- Conduct **basic sentiment analysis** using title/description and voice transcripts (YouTube)  
- Deliver polished outputs that combine **analysis with narrative and emotion**  
- Lay the foundation for **dashboarding or recommendation-based projects** in future phases  

---

# Project Structure 💫

YouTube_Netflix_Data_Analysis/
│
├── Project_part_1.ipynb # Data Cleaning, EDAs, Top Genres, etc for both YouTube and Netflix
├── Project_part_2_CLEAN.ipynb # Using of 3D charts and sankey chords for YouTube and Boxplots and Scatter Plots for Netflix 
├── Netflix_Part3.ipynb # Contains animation of various charts and dashboards with insights and KPIs
├── Copy_of_YouTube_part3_And_Over!.ipynb # contains highlights, insights, summary, documentary, tone polarity and many more!

---

## Key Features ❣️

### YouTube Analysis 

- Cleaned and transformed title, tag, description, and category data
- Extracted sentiment and emotional context using simple NLP tools
- Performed **voice-to-text conversion** on a sample to test emotional tone classification
- Created **GIFs and animated visuals** to convey mood evolution in trending videos
- Built **Chord Diagrams** to analyze tag interrelationships
- Created **Sankey Diagrams** to show category-view linkage flows
- Time-based heatmaps for views/likes/comments

### Netflix Analysis

- Cleaned release year, duration, country, language and genre data
- Generated country-level content with animated KPIs and dashboards
- Barplots for **top genres, countries, and languages**
- Explored trends in **movie duration** and **season length distributions**
- Built **mock dashboard visuals** that can be adapted later using Power BI tools or Tableau

--- 
  
## Notable Visual Techniques

| Chart Type             | Tool Used         | Purpose |
|------------------------|------------------|---------|
| Chord Diagrams         | Plotly | Tag relationship network (YouTube) |
| Sankey Flow Diagram    | Plotly            | Category → View flow mapping |
| Heatmaps               | Seaborn           | Time & country-wise content metrics |
| Animated Line Charts   | Matplotlib FuncAnimation | Sentiment over time |
| KPI Bar Charts         | Plotly Axes        | Netflix and YouTube country, genre, and duration analysis |
| GIF-based Highlights   | Imageio | Visual storytelling + transitions |
| Documetaries and HighLights  | MoviePy | Creative Visualisations and other Documentaries |


## Datasets Used 

| Platform  | Dataset | Source |
|-----------|---------|--------|
| YouTube   | [Trending YouTube Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new) | Kaggle |
| Netflix   | [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) | Kaggle |

> Both datasets are from 2020. Some portions were cleaned and sampled for optimal runtime and clarity of animation.

---

## Key Insights And Findings 💡

- **Entertainment** and **music** are consistently dominant across countries  
- Emotionally charged titles (🔥, 😂, WOW, OMG) leads to higher click-through and engagement  
- Videos with specific tags like "reaction", "official trailer", and "challenge" trend repeatedly  
- Sentiment skews **positive**, but sharp drops align with major global events or controversies  

### Netflix

- **Drama** and **documentaries** dominate post-2015  
- U.S., India, and U.K. form 60% of the content pool  
- The average movie runtime clusters around 90 minutes, while TV shows are often between 1-2 seasons  
- Non-English content saw a growth spike in 2018–2020  

---

## How to Run This Project 

All notebooks are fully runable in Google Colab or Jupyter based environments.

1. Clone this repository:

```bash
git clone https://github.com/shranya-cc/youtube-netflix-analysis.git
```
2. Open any notebook in Google Colab or locally
3. Install required packages if prompted:
```bash
pip install pandas matplotlib seaborn plotly textblob MoviePy Imageio
```
4. Run cells sequentially. GIFs and plot will render as outputs.

## Tools And Libraries Used:

- `pandas, numpy` – data wrangling

- `seaborn, matplotlib, plotly` – static and interactive visualizations

- `textblob, nltk` – basic NLP & sentiment scoring

- `Pillow, FuncAnimation` – GIF creation & animation

- `networkx` – chord diagrams & relationship graphs

- `Google Colab` – interactive notebook execution

## Future Enhancements 💐

* Add ML-based video popularity predictor

* Build interactive dashboards in Streamlit/Power BI

* Extend sentiment detection using BERT or transformer-based models

* Implement content recommendation system using NLP embeddings

* Add language detection and subtitle analysis

## About The Author 🌷

### Shranya Dutta
*Aspiring Data Analyst| Creative Coder| Data Storyteller*

Built to explore the art of transforming media data into engaging narratives through analytics and visuals.
If you liked this project, feel free to ⭐ the repository or connect on LinkedIn!

