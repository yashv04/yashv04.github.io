---
layout: single
title: "Sports Analytics & Strategy"
permalink: /sports-analytics/
---

## Sports Analytics & Strategy

I design **data-driven intelligence systems** that explain **why matches are won**, **which players truly matter**, and **how conditions and pressure shape outcomes**.

My work blends **cricketing context, machine learning, and clear storytelling** to support decision-making for teams, analysts, fantasy platforms, and broadcasters.

---

##  Core Focus Areas

- **Tactical prediction & match simulation**
- **Player impact and pressure performance modeling**
- **Venue- and condition-aware analytics**
- **Turning complex data into actionable cricket insights**

---

##  Tactical & Match Intelligence

### Match Simulator & Opponent Strategy Prediction _(Flagship)_

**Problem**  
In high-stakes T20 matches, anticipating an opponent’s tactical intent (powerplay aggression, death-over bowling plans, spin usage) provides a decisive edge. Traditional analysis is manual, slow, and reactive.

**Solution**  
Built an AI-powered tactical prediction engine that learns team-specific behaviors from historical IPL and T20 data to forecast strategies **before and during matches**.

**Approach**
- Ball-by-ball data collection from IPL & T20 leagues  
- Contextual feature engineering: match phase, venue, opposition, batsman & bowler types  
- Phase-wise modeling:
  - **Random Forest** for tactical pattern classification  
  - **XGBoost** for optimized decision boundaries  
- Team-specific matchup models (e.g., CSK vs RCB)

**Impact**
- Predictive insight into powerplay intent and death-over plans  
- Venue-aware tactical simulations  
- Shift from descriptive analysis to **predictive match intelligence**

---

### Live Win Probability Model

Built a real-time win probability engine that updates dynamically using ball-by-ball match data.

- Trained **Logistic Regression & Random Forest** models on historical T20/IPL data  
- Deployed as a **Streamlit application**  
- Identified death overs and run-rate stability as decisive match phases  

**Use cases:** Broadcasting graphics, analyst decision support, fantasy insights  

🔗 https://live-win-probability-mxjsrxex83jok9smfqwqyf.streamlit.app/

---

### ODI Pre-Match Win Predictor

A probabilistic model to estimate ODI match outcomes using team strength, venue, toss, and recent form.

- Feature engineering from cleaned ODI match & delivery datasets  
- Designed for analyst previews and fantasy platforms  

---

##  Player Impact & Performance Intelligence

### Impact Index Model & Auction Strategy _(Flagship)_

**Problem**  
Traditional metrics (runs, wickets) fail to capture a player’s true match impact.

**Solution**  
Designed a composite **Impact Index** combining batting, bowling, fielding, and contextual pressure.

**Methodology**
- **Batting:** runs, boundary %, partnerships  
- **Bowling:** wickets, economy, pressure creation  
- **Fielding:** catches, run-saving actions  
- **Context:** match pressure, chases, death overs  

**Applications**
- Auction strategy & squad planning  
- Fantasy team optimization  
- Role-based player deployment  

---

### Match-Winning Pressure Index

Quantified player performance in high-pressure situations such as tight chases and final overs.

- Identified consistent clutch performers  
- Useful for leadership roles and fantasy captaincy decisions  

🔗 https://public.tableau.com/app/profile/yash.vardhan6567/viz/T20IndexDashboard/T20PressureIndexDashboard

---

### Batsman vs Bowler Matchups

Interactive dashboard analyzing batter–bowler performance across phases and venues.

- Phase-wise insights: Powerplay, Middle, Death  
- Identified exploitable matchups and vulnerabilities  

🔗 https://public.tableau.com/app/profile/yash.vardhan6567/viz/BatsmanvsBowlersMatchup/BatsmanvsBowlerMatchupDashboardTillIPL2024

---

### AI-Powered Player Scouting

Machine learning–driven scouting system using **K-Means clustering** on normalized batter metrics.

- Role-based player archetypes  
- PCA & t-SNE for interpretability  
- Identification of undervalued players  

🔗 https://ai-powered-player-scouting-model-86df5borqdxszypxupgr5y.streamlit.app/

---

##  Venue & Conditions Intelligence

### Cricket Venue Intelligence Hub _(Flagship)_

Venue-centric analytics platform to decode how stadiums influence scoring, toss outcomes, and player performance.

**Key Features**
- Venue profiles: pitch behavior, boundary dimensions  
- Phase-wise scoring trends  
- **XGBoost-powered** score & win predictors  
- Venue-specific player recommendations  

🔗 https://cricket-venue-intelligence-app-mkbwla6gsdfdxqpdguihnx.streamlit.app/

---

### Smart Pitch Analysis Model

Pitch behavior classification using **CNN-based visual analysis** combined with machine learning.

- Predicts spin, swing, and bounce tendencies  
- Supports team strategy and fantasy decisions  

---

##  Data Storytelling & Cricket Narratives

### Virat Kohli – Test Career Analysis

Interactive analytical tribute capturing evolution, overseas dominance, partnerships, and leadership phases.

🔗 https://virat-test-story-7doohhp63qt4dyyfg7wx8n.streamlit.app/

---

### Rohit Sharma – Career Analytics Hub

Dual-dashboard project translating Rohit Sharma’s T20I and Test careers into data-driven narratives.

🔗 Test: https://rohit-sharma-test-career-ycbroxcnwmefkesca4kstx.streamlit.app/  
🔗 T20I: https://rohit-sharma-t20i-dashboard-nohflzrqecgvcaiezyxxhg.streamlit.app/

---

##  Final Note

These projects reflect my focus on building **practical, context-aware cricket intelligence systems** — where analytics directly informs strategy, performance, and decision-making.
