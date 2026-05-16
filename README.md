<div align="center">

# Yash Vardhan

**Sports CV Engineer** · Cricket Analyst · [`KhiladiPro`](https://www.khiladipro.com/)

[Portfolio](https://yashv04.github.io) · [LinkedIn](https://www.linkedin.com/in/yash-vardhan-5b3956169/) · [Email](mailto:yashv3110@gmail.com)

</div>

---

I'm a Sports CV engineer at KhiladiPro — I build production computer vision for live cricket and badminton: annotation pipelines, ball and shuttle tracking, action recognition, biomechanics. Outside work, I build public cricket analytics: a deployed ODI match predictor, IPL scouting models, fantasy XI optimization, venue intelligence.

> **Two halves of one path** — getting good enough to work on elite sport at the highest level.

---

## Featured Projects

Public cricket analytics — built in my own time, documented in detail at [yashv04.github.io](https://yashv04.github.io).

| Project | What it is | Stack |
|---|---|---|
| 🏏 **[ODI Full Match Predictor](https://github.com/yashv04/ODI-Full-Match-Predictor)** *(Flagship)* | 3-stage end-to-end ML system: pre-match win probability → live 1st innings projection → live 2nd innings chase probability. Calibrated, temporal splits, **91% death-over chase accuracy** on a 2024+ test set. Deployed. | LR · GBM · XGBoost · Streamlit |
| 🎯 **AI Player Scouting Model** | K-Means role clustering across 18-dimensional phase-specific player features. Auto-tags batters into PP / Middle / Death / All-phase specialists. Deployed. | scikit-learn · Streamlit |
| 🏟️ **[Cricket Venue Intelligence Hub](https://github.com/yashv04/Cricket-Venue-Intelligence-Hub)** | Multi-page Streamlit dashboard merging 4 IPL data sources. Single-venue deep dive, K-Means similarity clustering, composite predictive scoring, strategy recommendations. | Streamlit · K-Means · Plotly |
| 🎲 **Match Simulator + Opponent Strategy AI** | Markov-chain ball-by-ball simulator with venue/phase/bowler multipliers. ipywidgets dashboard. | NumPy · pandas |
| 💰 **Impact Index + Auction Strategy** | Integer Linear Program for auction squad optimization under a salary cap. PuLP solver, 543 eligible players, role-constrained selection. | PuLP · ILP |
| 🧪 **Smart Pitch + Fantasy XI** | Fantasy cricket system: rule-based venue tagging, faithful Dream11-schema scoring, LP optimizer for the optimal XI. Includes an honest writeup of target leakage caught in two ML experiments. | PuLP · pandas |

Each project has a full case study with architecture diagrams, honest limitations, and hard interview Q&A at **[yashv04.github.io](https://yashv04.github.io)**.

---

## What I Use Day-to-Day

**Computer Vision (at KhiladiPro)**
```
Python  ·  PyTorch  ·  OpenCV  ·  YOLOv8  ·  TrackNet  ·  MediaPipe  ·  FFmpeg
```

**Analytics (on my own time)**
```
pandas  ·  scikit-learn  ·  XGBoost  ·  Gradient Boosting  ·  Quantile Regression
K-Means  ·  ICC-style Elo  ·  isotonic calibration  ·  PuLP (ILP)
```

**Delivery**
```
Streamlit  ·  GitHub Pages  ·  Streamlit Community Cloud  ·  Git  ·  Jupyter
```

---

## How I Think About The Work

- **Pipeline beats model.** 80% of every project I've shipped was clean data, careful joins, and parsing edge cases. The model is the last 20%.
- **Match the model to the data.** Reaching for XGBoost on 2,000 rows is a tell. On the ODI predictor, Logistic Regression beat XGBoost by 9.7 percentage points on validation. Choose models for their *inductive bias*, not their reputation.
- **Honest metrics or none.** A `1.0` accuracy is a signal to investigate, not celebrate. Calibration matters more than peak accuracy — a well-calibrated 60% beats a miscalibrated 90%.
- **Document obsessively.** Every project page on my portfolio has a Limitations section that lists real bugs by line number. *The writing is the work.*

More on this at [yashv04.github.io/about](https://yashv04.github.io/about/).

---

## Open to Conversation

If you're working on **cricket or badminton CV at scale** — broadcaster analytics, franchise data teams, ICC initiatives, sports-tech startups, academic biomechanics labs — drop a line.

📧 **yashv3110@gmail.com**  
🔗 [linkedin.com/in/yash-vardhan-5b3956169](https://www.linkedin.com/in/yash-vardhan-5b3956169/)  
🌐 [yashv04.github.io](https://yashv04.github.io)
