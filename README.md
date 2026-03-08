# 🏀 Adnan's HackUTA App – NBA Top Scorers

A small interactive NBA statistics app built during **HackUTA at The University of Texas at Arlington**.

This project started as a spontaneous challenge during the hackathon when I brought my nephew and his friend (a UTA student) along to experience the event. I told him we were going to build an app together — he didn't believe me at first.

He has been obsessed with sports statistics since he was a kid. At **3–4 years old he could already memorize player stats**, so we decided to build something centered around NBA data.

By the end of the event we had built a working interactive app that pulls **live NBA scoring data** and visualizes the league’s top scorers.

Seeing something go from **idea → code → working application** was an awesome experience for both of us.

It was also my **first real taste of building something end-to-end**.

---

# 🚀 Features

The app pulls **live NBA statistics** and allows users to explore the league's top scorers.

Features include:

🏀 Load the **Top 10 NBA scorers**

🏆 Visual **Top 3 podium display**

📊 Interactive **bar chart comparison**

📋 Full **stat table including points, rebounds, and assists**

🖼 Player **headshots pulled dynamically**

🎨 Custom UI styling with NBA themed visuals

---

# 🧠 Technologies Used

- **Python**
- **Streamlit** – interactive web app framework
- **Pandas** – data processing
- **Requests** – API calls
- **Plotly** – interactive data visualization
- **NBA Stats API** – live player statistics

---

# ⚙️ How It Works

The app pulls data directly from the NBA statistics API.

```python
url = "https://stats.nba.com/stats/leagueLeaders"
