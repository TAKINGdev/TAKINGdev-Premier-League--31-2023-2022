![Project Cover](COVER.png)
# 🚀⚽ FOOTBALL LEAGUE TABLE ANALYSIS WITH PANDAS ⚽🚀

---

<p align="center">
  <img src="https://media.giphy.com/media/3o7qE1YN7aBOFPRw8E/giphy.gif" width="400" alt="football animation" />
</p>

---

## 📊 ABOUT THE PROJECT

Welcome to **Football League Table Analysis** — a **Python & pandas** based project to extract 🔥 key insights 🔥 from a football league dataset.

You will find detailed analyses of teams’ performances, including goals, wins, losses, points, and their qualification/relegation status.

---

## 🗂️ DATASET DESCRIPTION

The CSV file used here is called:


It includes the following columns:

| Column Name                 | Description                                |
| --------------------------- | ------------------------------------------ |
| `Team`                      | Name of the football team                   |
| `W`                         | Number of Wins                              |
| `D`                         | Number of Draws                             |
| `L`                         | Number of Losses                            |
| `GF`                        | Goals For (scored)                          |
| `GA`                        | Goals Against (conceded)                    |
| `GD`                        | Goal Difference (GF - GA)                   |
| `Pts`                       | Points earned                               |
| `Qualification or relegation` | Team's qualification or relegation status |

---

## 🧹 DATA PREPROCESSING STEPS

- ✅ Fixed `GD` column by replacing special minus signs with standard `-`
- ✅ Converted `GD` column to integer type
- ✅ Filled missing values in `Qualification or relegation` with `"No qualification"`

---

## 📌 ANALYSIS PERFORMED

| 🔍 Question                                                                                            | 🔥 Result Type               |
| ---------------------------------------------------------------------------------------------------- | --------------------------- |
| 1️⃣ Which teams scored **more than 60 goals** but have **less than 60 points**?                       | Filtered dataframe          |
| 2️⃣ Among teams with **no qualification**, which has the **best goal difference (GD)**?              | Single team info            |
| 3️⃣ Calculate **Win/Loss ratio** (W divided by L) and show top 3 teams                               | Sorted dataframe            |
| 4️⃣ Teams with **equal number of draws and wins**                                                    | Filtered dataframe          |
| 5️⃣ Teams with **GA > 65** but **not relegated**                                                    | Filtered dataframe          |
| 6️⃣ Average points of teams starting with the letter **B**                                          | Single numeric value        |
| 7️⃣ Teams with **wins < 10** but still **relegated**                                                | Filtered dataframe          |
| 8️⃣ Team with the **most draws (D)**                                                                | Single team info            |
| 9️⃣ Calculate **goals scored per win ratio (GF/W)** for Arsenal and Manchester City                   | Single numeric values       |

---

## 🚀 HOW TO RUN THIS PROJECT

1. Download or place the `LeagueTable.csv` file in the project root directory  
2. Make sure you have **Python 3.x** installed  
3. Install dependencies by running:  
   ```bash
   pip install pandas```

## 📦 REQUIREMENTS
Python 3.x

pandas library

## 🙌 THANK YOU!
Feel free to ⭐ this repo if you find it useful and share your feedback!

<p align="center"> <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="250" alt="thank you" /> </p>
Made with ❤️ and ⚽ by TAKINGdev
