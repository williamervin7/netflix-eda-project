# Netflix 1990s Movie Analysis

<img src="redpopcorn.jpg" alt="Red Popcorn" style="display: block; margin: auto; width: 300px;"/>

## 🎬 Overview
This project explores **Netflix's 1990s movie catalog** using exploratory data analysis (EDA). With the rise of streaming, understanding trends from past decades can help production companies spot nostalgic styles and audience preferences.

We analyze data from `netflix_data.csv` to answer key questions about movie genres, durations, countries of origin, and more — with a special focus on the most popular durations and trends across the 1990s.

---

## 📊 Table of Contents
- [The Dataset](#the-dataset)
- [Key Questions Explored](#key-questions-explored)
- [Visualizations](#visualizations)
- [Key Findings](#key-findings)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [License](#license)

---

## 📁 The Dataset
**`netflix_data.csv`** contains information on Netflix shows and movies, with the following relevant columns:

| Column         | Description                     |
|----------------|---------------------------------|
| `show_id`      | The unique ID of the show       |
| `type`         | Movie or TV Show                |
| `title`        | Title of the show               |
| `director`     | Director name                   |
| `cast`         | Main cast members               |
| `country`      | Country of origin               |
| `date_added`   | Date added to Netflix           |
| `release_year` | Year of Netflix release         |
| `duration`     | Duration in minutes             |
| `description`  | Short description of the show   |
| `genre`        | Genre of the show or movie      |

---

## ❓ Key Questions Explored
- What was the most common movie duration in the 1990s?
- How many short Action movies (under 90 mins) were released in that decade?
- What were the top 10 genres for 1990s Netflix movies?
- What was the average duration of Comedy movies?
- Which country produced the most movies?
- Which director had the most releases?
- How many TV shows were added to Netflix after 2015?

---

## 📈 Visualizations
- **Bar chart** of movies with the most frequent duration by release year
- **Bar chart** of top genres in the 1990s
- **Histogram** of 1990s movie durations
- **Pie chart** of movie production by country
- **Bar chart** of TV shows added post-2015

_All plots generated using Matplotlib._

---

## 🔍 Key Findings
- The most common movie duration in the 1990s was 93 minutes.
- There were 7 short Action movies** released in the decade.
- The **most frequent genre** was Action.
- Average duration of Comedy movies was 110.7 minutes.
- The United States led in 1990s movie production on Netflix.
- The director with the most releases was Johnnie To.

---

## 🛠 Technologies Used
- Python
- Pandas
- Matplotlib
- NumPy

---

## ▶️ How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/netflix-1990s-analysis.git
   cd netflix-1990s-analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib numpy
   ```
3. Run the Jupyter Notebook or Python script.

---

## ✨ Credits
This project was completed as part of a data science learning path, inspired by the nostalgic vibe of 90s cinema!

---

Feel free to fork, contribute, or build on it for your own retro-flavored analysis!

