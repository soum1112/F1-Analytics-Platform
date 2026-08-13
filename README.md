# 🏎️ F1 Analytics Platform — 2025 Season

An end-to-end data analytics project built using real Formula 1 race data.

## 📌 Project Overview
This project collects, cleans, stores, analyses, and visualises 2025 F1 race data across 5 Grand Prix events: Bahrain, Saudi Arabia, Japan, Miami, and Monaco.

## 🛠️ Tools & Technologies
- **Python** — data collection, cleaning, analysis
- **FastF1 API** — real F1 telemetry and race data
- **Pandas** — data manipulation
- **Matplotlib** — data visualisation
- **SQLite** — relational database
- **SQLAlchemy** — Python to SQL connection
- **Power BI** — interactive dashboard

## 📁 Project Structure
F1_Analytics/
├── data/ # Raw and cleaned CSV files (5 races)
├── notebooks/ # Jupyter notebooks (collection, cleaning, database, analysis)
├── sql/ # SQLite database
├── reports/ # Analysis charts (PNG) and Power BI dashboard (PDF)
└── dashboard/ # Power BI .pbix file

## 📊 Analysis Questions Answered
1. Who scored the most points across 5 races?
2. Which team performed best overall?
3. Does qualifying position affect race finish?
4. Which driver had the fastest average lap time?
5. How does tyre compound affect lap time?
6. Which driver gained the most positions from grid to finish?

## 🔑 Key Findings
- McLaren dominated the opening 5 races with Piastri leading on 105 points
- Strong correlation between qualifying position and race finish for top 5 starters
- Tyre degradation makes soft compounds appear slower on average despite being fastest when new
- Oliver Bearman showed the most overtaking ability, gaining 10 positions in a single race

## 📈 Dashboard
Built in Power BI with 3 pages:
- **Driver Performance** — points standings and positions gained
- **Team Performance** — team points and average finish position
- **Race Summary** — race-by-race results and points progression
