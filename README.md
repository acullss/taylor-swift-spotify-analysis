# Taylor Swift Spotify Charts Analysis

## Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on Spotify chart data to examine the popularity and performance of Taylor Swift's songs over time.  

Using a large Spotify charts dataset (~3.4GB), this analysis focuses on how certain songs maintain popularity and how their performance changes across Spotify chart categories such as **Top 200** and **Viral 50**.

The project particularly explores the chart performance of several Taylor Swift songs, including **Lover**, **Delicate**, and **Love Story (Taylor's Version)**, to understand patterns of long-term popularity and viral streaming behavior.

---

## Project Objectives
The main objectives of this project are:

- To analyze the performance of Taylor Swift songs on Spotify charts
- To understand trends in song popularity over time
- To compare long-term chart longevity versus short viral peaks
- To identify how streaming behavior influences chart rankings

---

## Dataset
The dataset used in this project comes from the **Spotify Charts dataset** available on Kaggle.
It contains daily chart information for songs appearing on Spotify charts worldwide.

### Dataset Features
The dataset includes the following attributes:

- **Artist** – Name of the artist
- **Song Title** – Title of the track
- **Date** – Daily chart record date
- **Rank** – Song position on the chart
- **Streams** – Number of daily streams
- **Chart Type** – Chart category (Top 200 / Viral 50)

This dataset enables analysis of how songs move across charts and how long they remain popular.

---

## Tools & Technologies
The analysis was conducted using the following tools:

- **Python** – Main programming language
- **Apache Spark (PySpark)** – Used for handling large-scale data processing
- **Pandas** – Data manipulation and aggregation
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive analysis environment

---

## Key Insights
From the exploratory analysis of Taylor Swift songs, several insights were observed:

### 1️. Chart Longevity
The song **Lover** shows strong long-term popularity and continues to appear in Spotify charts over an extended period. This indicates consistent listener engagement.

### 2️. Viral Peaks
Songs such as **Love Story (Taylor’s Version)** experienced a strong surge in popularity shortly after release, demonstrating how new releases often generate temporary viral spikes.

### 3️. Song Lifecycle
The song **Delicate** showed strong performance between **2018 and 2020** before gradually declining, illustrating the natural lifecycle of many popular songs.

---

## Analysis Workflow
The analysis followed a typical data analysis process:

1. **Data Collection**  
   Importing the Spotify chart dataset.

2. **Data Cleaning**  
   Filtering the dataset to focus on Taylor Swift songs.

3. **Exploratory Data Analysis (EDA)**  
   Examining streaming numbers and chart rankings.

4. **Visualization**  
   Creating charts to observe trends and popularity patterns.

---

## Project Structure
taylor-swift-spotify-analysis
│
├── exploratory-data-analysis-taylor-swift.ipynb
├── README.md
└── charts.csv (dataset)

---

## How to Run the Project
To view the analysis:
1. Download or clone this repository
2. Open the file `exploratory-data-analysis-taylor-swift.ipynb`
3. Run the notebook using **Jupyter Notebook** or **Google Colab**

---

## Author
Student Data Analysis Project  
Course: **Data Warehouse and Business Intelligence**
Project Topic: **Spotify Chart Analysis of Taylor Swift Songs**
