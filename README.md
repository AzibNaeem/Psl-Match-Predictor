# 🏏 PSL Match Predictor
 
Welcome to the **PSL Match Predictor**, a 🔥 data-driven tool to forecast Pakistan Super League (PSL) match outcomes with style and precision! Powered by machine learning, this project analyzes **10 seasons of PSL data (2016–2025)** to predict who’ll dominate the pitch.

Whether you’re a cricket fanatic, a data geek, or just love cool tech, this repo has something for you! 🎉

---

## 🌟 Why is this awesome?

- Predicts match winners with a **RandomForest** model 📈  
- Crunches **320+ matches and player stats** (runs, wickets, catches) 🧮  
- Visualizes team performance with **sleek charts** 📊  
- Easy-to-use **Python code** with a professional setup 🐍  

---

## 🎯 Features

| Feature         | Description                                                             | Sticker |
|-----------------|-------------------------------------------------------------------------|---------|
| Match Prediction| Forecast PSL match outcomes with win probabilities (e.g., Karachi Kings: 64%) | 🏆      |
| Player Stats    | Track runs, wickets, and catches for 11 players per team per match     | 🧑‍💼     |
| Team Analysis   | Compare team win rates, rankings, and chemistry scores                 | 📋      |
| Visualizations  | Generate bar charts and performance trends                             | 📊      |
| Data Simulation | 10 seasons of realistic PSL data (2016–2025)                           | 🗄️       |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`
- A passion for cricket! 🏏

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/psl-match-predictor.git
cd psl-match-predictor

# Install dependencies
pip install -r requirements.txt

# Run the main script
python main.py
```

🎈 **Pro Tip:** Check out `psl_teams.json` for team data and tweak rosters for custom predictions!

---

## 🛠️ How It Works

### 📅 Data Simulation

- Generates ~320 matches (2016–2025) with team stats (runs, wickets, venue) and player stats.
- Example: Babar Azam’s runs, Shaheen Afridi’s wickets.

### 🧠 Model Training

- Uses a `RandomForestClassifier` with features like win rates, form, head-to-head, and team chemistry.
- Achieves ~**92% test accuracy** on simulated data.

### 🔮 Prediction

- Predicts match outcomes with percentage probabilities.  
  Example: Karachi Kings 64% vs. Lahore Qalandars 36%.
- Outputs a clean dictionary with predicted winner and model accuracy.

### 📂 Outputs

- **CSVs**: `psl_match_data_2016_2025.csv`, `psl_player_stats_2016_2025.csv`
- **Visuals**: `team_stats.png`, `<team>_trend.png`
- **JSON**: `psl_teams.json`

---

## 📈 Example Output

Predicting a match between Karachi Kings and Lahore Qalandars:

```json
{
    "Team1": "Karachi Kings",
    "Team2": "Lahore Qalandars",
    "Karachi Kings_Win_Probability": 64.0,
    "Lahore Qalandars_Win_Probability": 36.0,
    "Predicted_Winner": "Karachi Kings",
    "Model_Accuracy": 92.0
}
```

🌟 **Sticker Alert:** Check `psl_team_stats.csv` for team rankings and `psl_detailed_player_stats.csv` for top performers! 🥇

---

## 🏗️ Project Structure

```
psl-match-predictor/
├── main.py                 # Main script
├── psl_teams.json          # Team and player data
├── psl_match_data_*.csv    # Match data output
├── psl_player_stats_*.csv  # Player stats output
├── team_stats.png          # Team comparison chart
├── requirements.txt        # Dependencies
└── README.md               # You’re here! 😎
```

---

## 🤝 Contributing

Love cricket and code? We’d love your help! 🙌

1. Fork the repo 🍴  
2. Create a branch: `git checkout -b feature/cool-idea`  
3. Commit your changes: `git commit -m "Added cool idea"`  
4. Push to the branch: `git push origin feature/cool-idea`  
5. Open a Pull Request 🚀  

### Ideas to Contribute:

- Add real PSL data 📊  
- Include player-specific features (e.g., strike rates) ⚡  
- Build a web interface for predictions 🌐  

---

## 📜 License

This project is licensed under the **MIT License**. See `LICENSE` for details.

---

## 🙏 Acknowledgments

- **PSL** for the epic cricket action 🏏  
- **Python community** for awesome libraries 🐍  
- **You**, for checking out this repo! 🎉  

---

## 📬 Contact

- GitHub: [AzibNaeem](https://github.com/AzibNaeem)  
- Email: azibnaeem17official@gmail.com

---

**Sticker Wall:** 🏏🔮📈🥇  
Built with 💖 for cricket fans and data nerds!
