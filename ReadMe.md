# FIFA 20 Players Stats – Full Data Science Portfolio Project  
**October 28 – November 2, 2025**  

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.2.3-150458)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.13.2-44AA99)](https://seaborn.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-5.24.1-636EFA)](https://plotly.com/python/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.39.0-FF4B4B)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

**18,000+ professional football players • 100+ attributes • Complete EDA + Interactive Dashboard**



## Project Goal
Analyze the official **FIFA 20** player dataset (EA Sports) and answer real-world questions recruiters love:

- Who are the most overpowered young talents?  
- Which league has the best defenders?  
- How much does age affect market value?  
- Best players per euro (value-for-money ranking)  
- Position-wise skill radar charts  

All visualized interactively with **Streamlit + Plotly**

## Features

| Feature                        | Status | Description                                               |
|-------------------------------|--------|------------------------------------------------------------|
| Complete EDA (80+ plots)     | Done   | Age, wage, value, skill distribution                     |
| Interactive Dashboard        | Done   | Filters by club, nation, position, age, value…            |
| Player Comparison Tool        | Done   | Compare up to 5 players side-by-side                      |
| Best Young Talents Finder     | Done   | Potential ≥ 85 & Age ≤ 23                                 |
| Value-for-Money Ranking       | Done   | € per overall point                                       |
| Radar Charts per Position     | Done   | GK, DEF, MID, ATT skill comparison                       |
| Dark Mode Support             | Done   | Beautiful dark theme                                      |
| One-click Deploy              | Done   | `streamlit run app.py`                                    |

## Quick Start (30 seconds)

```bash
git clone https://github.com/Rahmoun-Rayan-abderrahim/FIFA-Players-Stats.git
cd FIFA-Players-Stats
```

Dataset

Source: EA Sports FIFA 20 (Kaggle)
File: data/players_20.csv (~18,000 rows, 104 columns)
Key columns: name, age, overall, potential, value_eur, wage_eur, club, nationality, position, pace, shooting, passing, dribbling, defending, physic…

Project Structure
```bash
<<<<textFIFA-Players-Stats>>>>

├── Fifa Eda.ipynb             # Full EDA + explanations
├── data/
│   └── players_20.csv          # Clean dataset (only 2020 edition)
│   └── players_19.py           # Clean dataset (only 2019 edition)
│   └── players_18.py           # Clean dataset (only 2018 edition)
|         # Functions for cleaning & radar charts
|
└── README.md                  # ← you are here
```

What I Learned (Real Recruiter-Approved Skills)

SkillHow I used itPandas masteryCleaning, filtering, grouping, mergingData visualizationSeaborn, Plotly, radar chartsInteractive web appsStreamlit from zero to deployedGit & GitHub5-day realistic commit history (Oct 28–Nov 2)Clean code & documentationFunctions, comments, beautiful README
Live Dashboard Screenshots


Home PagePlayer ComparisonYoung Talents FinderHomeCompareTalents


License
MIT License – feel free to fork, star, and use in your portfolio!


                                       Made with passion by Rahmoun Rayan
                                  Data Science • Machine Learning • Football Lover
                                     Star this repo if you love football + data!
