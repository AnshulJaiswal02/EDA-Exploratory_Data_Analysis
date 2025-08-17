# Exploratory Data Analysis of International Volleyball Players

## 🏐 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on a dataset of international volleyball players. The primary goal is to uncover patterns, relationships, and insights regarding players' physical attributes, demographic information, and professional roles. By analyzing this data, we aim to answer key questions about what factors contribute to a player's position and national representation in the sport.

This analysis is a practical demonstration of data cleaning, manipulation, visualization, and statistical interpretation using Python's core data science libraries.

---

## 📊 Dataset

The dataset contains information on professional volleyball players, including:
* **Demographics:** Name, Country of Origin, Age, Gender
* **Physical Attributes:** Height, Weight, Spike Reach, Block Reach
* **Professional Details:** Player Position (e.g., Outside Hitter, Middle Blocker, Libero)

---

## 🎯 Key Questions Explored

1.  What is the demographic distribution of players (e.g., age, country of origin)?
2.  How do key physical attributes like **height**, **weight**, **spike reach**, and **block reach** vary across different player positions?
3.  Is there a significant correlation between a player's height and their spike/block reach?
4.  Which countries produce the highest number of professional players in this dataset?
5.  What are the typical physical profiles for specialized roles like **Libero** versus a **Middle Blocker**?

---

## 🛠️ Methodology & Tools

The analysis was conducted in a Jupyter Notebook environment, leveraging the following Python libraries:

* **Data Manipulation:** `pandas`
* **Data Visualization:** `matplotlib` and `seaborn`
* **Numerical Operations:** `numpy`

The EDA process followed these key steps:
1.  **Data Loading & Inspection:** Initial loading of the dataset and a high-level overview using `.info()`, `.describe()`, and `.shape`.
2.  **Data Cleaning:** Handled missing values (`.isnull().sum()`) and checked for duplicate entries to ensure data quality.
3.  **Univariate Analysis:** Analyzed individual features to understand their distributions (e.g., histograms for age and height, bar charts for player positions and countries).
4.  **Bivariate Analysis:** Explored relationships between pairs of variables using scatter plots, box plots, and correlation heatmaps to uncover insights.

---

## 📈 Key Findings & Visualizations

*(Note: Replace these examples with your actual findings!)*

* **Height is a Key Differentiator for Position:** The analysis revealed a strong distinction in height based on player position. **Middle Blockers** were, on average, the tallest players, while **Liberos** were the shortest, which aligns with the specialized defensive role they play.
    * *Visualization:* Box Plot of Height Distribution by Player Position.

* **Dominance of European Nations:** Countries like Brazil, Italy, and Russia were heavily represented in the dataset, indicating their strong presence in the professional volleyball circuit.
    * *Visualization:* Bar Chart showing the Top 10 Countries by Player Count.

* **Strong Positive Correlation in Reach Attributes:** A correlation heatmap showed a very strong positive correlation (**> 0.9**) between a player's height, spike reach, and block reach, confirming that taller players have a significant advantage in offensive and defensive plays at the net.
    * *Visualization:* Heatmap of Physical Attributes.

---

## 🚀 How to Run This Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AnshulJaiswal02/EDA-Exploratory_Data_Analysis.git](https://github.com/AnshulJaiswal02/EDA-Exploratory_Data_Analysis.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd EDA-Exploratory_Data_Analysis
    ```
3.  **Install the required libraries:**
    ```bash
    pip install pandas matplotlib seaborn jupyterlab
    ```
4.  **Launch Jupyter Lab and open the notebook:**
    ```bash
    jupyter lab
    ```

---