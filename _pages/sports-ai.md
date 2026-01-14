---
layout: single
title: "Sports AI & Computer Vision"
permalink: /sports-ai/
classes: wide
author_profile: true
---

## What I work on

I design and build **end-to-end AI systems** for sports performance analysis, focusing on computer vision and multimodal learning.

My work spans:
- Object detection & keypoints
- Ball & shuttle tracking
- Action recognition & shot classification
- Sports biomechanics & motion analysis

Below are selected projects that reflect **real-world sports problems**, engineering depth, and applied outcomes.


### Ball & Shuttle Tracking using TrackNet

**Problem**  
Accurate tracking of fast-moving objects like a cricket ball or badminton shuttle is critical for performance analysis, speed estimation, and downstream biomechanics. However, tracking reliability often degrades due to high velocity, motion blur, occlusion, and varying camera angles.

**System Overview**  
I built and evaluated a TrackNet-based tracking pipeline to detect and track ball and shuttle trajectories frame-by-frame across cricket and badminton footage.

**Engineering Details**  
- Owned the end-to-end workflow, including dataset preparation, frame extraction, and ground-truth coordinate annotation  
- Fine-tuned TrackNet models on sport-specific data to improve robustness across different environments  
- Performed inference and testing on unseen match and practice clips  
- Conducted detailed error analysis by comparing predicted trajectories against ground-truth coordinates to identify failure cases

**Evaluation & Validation**  
- Quantitative evaluation using ground-truth vs predicted pixel distance error  
- Qualitative validation via visual overlay of predicted and ground-truth trajectories  
- Clip-level success vs failure analysis to assess robustness under fast motion and partial occlusion  
- Trajectory continuity and smoothness checks to validate temporal consistency

**Sports Insight & Impact**  
The improved tracking pipeline provides a reliable foundation for advanced sports analytics, including speed estimation, shot quality assessment, and biomechanics analysis. This work enables scalable, automated analysis that reduces reliance on manual tagging.

**Tech Stack**  
Python, OpenCV, PyTorch, TrackNet, FFmpeg

### Cricket Hit vs Miss Detection (Audio-Based)

**Problem**  
Accurately detecting bat–ball contact events is essential for automated shot segmentation and batting analysis. Manual tagging is time-consuming and inconsistent, while visual-only approaches often struggle under occlusion and camera variability.

**System Overview**  
I built an audio-based hit vs miss detection system to classify bat–ball contact events from short cricket clips using acoustic signals.

**Engineering Details**  
- Owned the complete pipeline, including audio annotation, feature extraction, model training, and threshold tuning  
- Designed features to capture acoustic signatures associated with bat–ball contact  
- Performed extensive error analysis to reduce false positives and false negatives across diverse recording conditions

**Evaluation & Validation**  
- Evaluated model performance using accuracy, precision, and recall metrics  
- Conducted manual clip-level validation to verify predictions against ground truth labels  
- Iteratively tuned decision thresholds based on observed failure cases

**Sports Insight & Impact**  
This system enables reliable detection of bat–ball contact events, forming a critical building block for automated shot segmentation and scalable batting analysis without manual intervention.

**Tech Stack**  
Python, Audio Signal Processing, Machine Learning


### Badminton Smash Biomechanics & Speed Estimation

**Problem**  
Evaluating smash quality in badminton is traditionally subjective, relying on visual judgment rather than measurable performance metrics. Coaches need objective, video-based indicators to assess technique, power, and consistency.

**System Overview**  
I built a video-based biomechanics analysis pipeline to estimate smash speed and analyze motion characteristics using shuttle tracking and player keypoints, without relying on wearable sensors.

**Engineering Details**  
- Used shuttle trajectory outputs from a tracking model to compute frame-wise velocity and estimate smash speed  
- Integrated player keypoint data to analyze movement patterns and kinematic angles during smash execution  
- Designed calculations to work purely from video input, enabling scalable analysis in real-world settings

**Evaluation & Validation**  
- Performed visual verification of shuttle trajectories and biomechanical outputs to ensure correctness  
- Compared speed and motion patterns across multiple smash instances to validate consistency and reliability  
- Analyzed variations in kinematic angles to identify execution differences between attempts

**Sports Insight & Impact**  
This pipeline enables objective performance benchmarking of badminton smashes, supporting data-driven coaching feedback and skill assessment. It bridges the gap between raw tracking outputs and actionable biomechanical insights for player development.

**Tech Stack**  
Python, OpenCV, Computer Vision, Biomechanics Analysis

### Shot Type Classification (Cricket & Badminton)

**Problem**  
Manual labeling of shot types from match and training footage is time-consuming and inconsistent, limiting large-scale tactical and performance analysis across sports.

**System Overview**  
I developed shot type classification pipelines for cricket and badminton using short video clips to automatically identify stroke categories based on motion and temporal patterns.

**Engineering Details**  
- Created labeled datasets using short (2–3 second) video clips capturing complete shot executions  
- Extracted frame-based features to model spatio-temporal motion patterns  
- Trained and tested classification models for multiple shot categories across both sports  
- Performed error and confusion analysis to understand misclassification patterns and refine model behavior

**Evaluation & Validation**  
- Evaluated classification performance using standard metrics and confusion matrices  
- Conducted qualitative analysis on failure cases to identify visually similar shot patterns  
- Iteratively refined datasets and models based on observed classification errors

**Sports Insight & Impact**  
Automated shot classification enables scalable tagging of match footage, supports tactical breakdowns by shot selection, and contributes to player profiling through quantitative stroke distribution analysis.

**Tech Stack**  
Python, OpenCV, Machine Learning, Video Analytics


---

These projects reflect my focus on building **practical, end-to-end Sports AI systems** that translate raw data and video into actionable insights for analysts, coaches, and performance teams.
