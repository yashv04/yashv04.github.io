---
layout: single
title: "Applied Tactical & Performance Analytics"
permalink: /sports-analytics/
---
# Applied Tactical & Performance Analytics

## Overview

This section covers **downstream analytics systems** built on top of structured sports data — such as events, actions, player roles, and match context — to support **tactical decision-making and performance evaluation**.

While my primary specialization is **video-based performance intelligence**, these analytics systems demonstrate how extracted signals can be translated into **match strategy, player valuation, and venue-aware insights**.

---

## How This Fits Into My Work

In a complete sports intelligence stack:

- **Video & sensor systems** extract events, actions, and performance signals  
- **Analytics models** transform those signals into tactical and strategic insights  

This section represents the **decision layer** of that stack.

---

## Tactical & Match Intelligence Systems

### Match Simulator & Opponent Strategy Prediction (Flagship)

**Sports Problem**  
In high-stakes T20 matches, teams need to anticipate opponent intent — powerplay aggression, bowling plans, and phase-wise strategies — before patterns fully emerge.

**System Overview**  
A phase-wise tactical prediction system that models team behavior using historical ball-by-ball data and contextual match features.

**Approach**
- Context-aware feature engineering (phase, venue, opposition, player roles)  
- Phase-specific modeling using:
  - Random Forest for pattern learning  
  - XGBoost for optimized tactical classification  
- Team-specific matchup modeling (e.g., CSK vs RCB)

**Insights Enabled**
- Predictive understanding of phase-wise intent  
- Scenario-based tactical simulation  
- Support for pre-match and in-match planning

---

### Live Win Probability Engine

A real-time win probability system that updates dynamically using ball-by-ball match state.

**Key Elements**
- Logistic Regression and Random Forest models  
- Emphasis on phase transitions and pressure situations  
- Interactive Streamlit deployment

**Use Cases**
- Broadcast graphics  
- Analyst decision support  
- Fantasy platforms  

<https://live-win-probability-mxjsrxex83jok9smfqwqyf.streamlit.app/>

---

### ODI Pre-Match Win Predictor

A probabilistic model estimating ODI match outcomes using team strength, venue, toss, and recent form.

**Purpose**
- Analyst previews  
- Scenario comparison  
- Fantasy decision support  

<https://odi-pre-match-win-predictor-cvacrsmbuds2t5cn5bdpwg.streamlit.app/>

---

## Player Impact & Performance Modeling

### Impact Index & Auction Strategy (Flagship)

**Sports Problem**  
Traditional statistics fail to capture a player’s true influence on match outcomes, especially under pressure.

**System Overview**  
A composite player impact model combining batting, bowling, fielding, and contextual performance.

**Modeling Components**
- Batting contribution and partnership impact  
- Bowling efficiency and pressure creation  
- Fielding value estimation  
- Contextual weighting (chases, death overs)

**Applications**
- Auction and squad planning  
- Role-based player deployment  
- Fantasy optimization

---

### Pressure Performance Index

A specialized model quantifying player effectiveness in high-pressure situations.

**Insights Enabled**
- Identification of clutch performers  
- Leadership and role suitability analysis  

<https://public.tableau.com/app/profile/yash.vardhan6567/viz/T20IndexDashboard/T20PressureIndexDashboard>

---

### Batter vs Bowler Matchup Analysis

Interactive analysis of batter–bowler performance across match phases and venues.

**Insights Enabled**
- Exploitable matchups  
- Phase-specific vulnerabilities  
- Tactical bowling and batting plans  

<https://public.tableau.com/app/profile/yash.vardhan6567/viz/BatsmanvsBowlersMatchup/BatsmanvsBowlerMatchupDashboardTillIPL2024>

---

## Venue & Conditions Intelligence

### Cricket Venue Intelligence Hub (Flagship)

A venue-centric intelligence platform decoding how stadium characteristics influence scoring, toss outcomes, and player performance.

**Key Features**
- Venue-specific scoring and phase trends  
- Pitch and boundary influence analysis  
- XGBoost-based score and win predictors  
- Venue-aware player recommendations  

<https://cricket-venue-intelligence-app-mkbwla6gsdfdxqpdguihnx.streamlit.app/>

---

## Data Storytelling & Analytical Narratives

These projects focus on **explaining performance evolution and context**, combining analytics with clear narrative structure.

- Virat Kohli — Test Career Analysis  
  <https://virat-test-story-7doohhp63qt4dyyfg7wx8n.streamlit.app/>

- Rohit Sharma — Career Analytics Hub  
  Test: <https://rohit-sharma-test-career-ycbroxcnwmefkesca4kstx.streamlit.app/>  
  T20I: <https://rohit-sharma-t20i-dashboard-nohflzrqecgvcaiezyxxhg.streamlit.app/>

---

## Why This Section Matters

These analytics systems demonstrate my ability to:
- Convert structured events and context into decisions  
- Support coaches, analysts, and strategists  
- Build the **final intelligence layer** on top of vision-driven signals
