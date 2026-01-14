---
layout: single
title: "Sports Analytics & Strategy"
permalink: /sports-analytics/
---

I design data-driven intelligence systems that explain why matches are won, which players truly matter, and how conditions and pressure shape outcomes.
My work blends cricketing context, machine learning, and clear storytelling to support decision-making for teams, analysts, fantasy platforms, and broadcasters.

My focus areas include:

Tactical prediction and match simulation

Player impact and pressure performance modeling

Venue- and condition-aware analytics

Translating complex data into actionable cricket insights

Tactical & Match Intelligence
Match Simulator & Opponent Strategy Prediction (Flagship)

Problem
In high-stakes T20 matches, anticipating an opponent’s tactical intent (powerplay aggression, death-over bowling plans, spin usage) provides a decisive edge. Traditional tactical insights rely heavily on manual video analysis, which is slow and reactive.

Solution
Built an AI-powered tactical prediction engine that learns team-specific behaviors from historical T20 and IPL data to forecast likely strategies before and during matches.

Approach

Collected and processed ball-by-ball data from IPL and T20 leagues

Engineered contextual features including match phase, venue, opposition, batsman type, bowler type, and game situation

Trained phase-specific models:

Random Forest to classify tactical patterns (e.g., yorker-heavy, spin-dominant, aggression-first)

XGBoost to optimize decision boundaries for tactical outcomes

Developed team-specific matchup models (e.g., CSK vs RCB) to capture rivalry and venue effects

Key Insights

Identified aggressive powerplay intent for specific teams with high confidence

Detected venue-dependent shifts in middle and death-over strategies

Enabled scenario-based match simulations for tactical planning

Impact
Transforms tactical analysis from descriptive reporting into predictive match intelligence.

Live Win Probability Model

Built a real-time win probability engine that dynamically updates a team’s chances of winning using ball-by-ball inputs such as wickets, runs, overs remaining, and match momentum.

Trained Logistic Regression and Random Forest models on historical T20/IPL data

Deployed as a Streamlit app for live match usage

Revealed how run-rate stability and death-overs execution dominate match outcomes

Applications: Broadcasting graphics, analyst decision support, fantasy insights
🔗 Live App: https://live-win-probability-mxjsrxex83jok9smfqwqyf.streamlit.app/

ODI Pre-Match Win Predictor

Developed a pre-match prediction model that estimates ODI match outcomes using team strength, venue, toss, form, and historical performance indicators.

Feature engineering from cleaned ODI match and delivery datasets

Probabilistic modeling to support pre-match planning and expectations

Designed for analyst previews and fantasy platforms

Player Impact & Performance Intelligence
Impact Index Model & Auction Strategy (Flagship)

Problem
Traditional metrics like runs and wickets often fail to capture a player’s true influence on match outcomes.

Solution
Designed a composite Impact Index that quantifies holistic match contribution across batting, bowling, fielding, and context.

Methodology

Batting: runs, boundary percentage, partnerships

Bowling: wickets, economy, pressure creation

Fielding: catches, run-saving actions

Context: match situation, pressure moments, death overs

Insights

Identified high-impact players whose value exceeds traditional stats

Highlighted players excelling in low-scoring or high-pressure matches

Applications

Auction strategy and squad construction

Fantasy team optimization

Role-based player deployment

Match-Winning Pressure Index

Created a Pressure Index to evaluate player performance in high-stakes situations such as tight chases and final overs.

Quantified clutch performance beyond aggregate stats

Identified consistent pressure performers vs underperformers

Useful for leadership decisions and fantasy captaincy picks

🔗 Dashboard: https://public.tableau.com/app/profile/yash.vardhan6567/viz/T20IndexDashboard/T20PressureIndexDashboard

Batsman vs Bowler Matchups

Developed an interactive matchup dashboard to analyze batter performance against specific bowlers across phases and venues.

Phase-wise analysis: Powerplay, Middle, Death

Identified exploitable matchups and hidden vulnerabilities

Built using Python + Tableau for analyst-friendly exploration

🔗 Dashboard: https://public.tableau.com/app/profile/yash.vardhan6567/viz/BatsmanvsBowlersMatchup/BatsmanvsBowlerMatchupDashboardTillIPL2024

AI-Powered Player Scouting

Built a machine learning–driven scouting system using K-Means clustering on normalized batter metrics.

Identified role-based player archetypes

Used PCA and t-SNE for interpretability

Enabled discovery of undervalued players and optimal team combinations

🔗 App: https://ai-powered-player-scouting-model-86df5borqdxszypxupgr5y.streamlit.app/

Venue & Conditions Intelligence
Cricket Venue Intelligence Hub (Flagship)

Designed a venue-centric analytics platform to decode how stadiums influence scoring patterns, toss outcomes, and player performance.

Features

Venue profiles: average scores, pitch behavior, boundary dimensions

Phase-wise scoring trends

XGBoost-powered score and win predictors

Venue-specific player recommendations

Impact
Helps teams and analysts optimize match strategies and player selection based on venue intelligence.

🔗 App: https://cricket-venue-intelligence-app-mkbwla6gsdfdxqpdguihnx.streamlit.app/

Smart Pitch Analysis Model

Built a pitch classification system combining CNN-based visual analysis with machine learning models to predict pitch behavior (spin, swing, bounce).

Supports strategy formulation and fantasy decision-making

Bridges visual data with structured match analytics

Data Storytelling & Cricket Narratives
Virat Kohli – Test Career Analysis

An interactive analytical tribute capturing the evolution, overseas dominance, partnerships, and leadership phases of Virat Kohli’s Test career.

🔗 App: https://virat-test-story-7doohhp63qt4dyyfg7wx8n.streamlit.app/

Rohit Sharma – Career Analytics Hub

A dual-dashboard project analyzing Rohit Sharma’s T20I and Test careers, translating raw numbers into a narrative of adaptability and legacy.

🔗 Test: https://rohit-sharma-test-career-ycbroxcnwmefkesca4kstx.streamlit.app/

🔗 T20I: https://rohit-sharma-t20i-dashboard-nohflzrqecgvcaiezyxxhg.streamlit.app/
