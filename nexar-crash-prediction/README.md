# Binary Prediction with Dashcam Dataset

This folder contains our work for the [Nexar Dashcam Crash Prediction Challenge](https://www.kaggle.com/competitions/nexar-collision-prediction) hosted on Kaggle.

The goal of this competition is to build a model that predicts imminent vehicle collisions or near-misses using real-world dashcam videos. The task is framed as a binary classification problem, where both collisions and near-misses are considered positive cases.

## Competition Overview
- **Type**: Binary Classification (Collision / No Collision)  
- **Goal**: Predict imminent collisions or near-misses from dashcam videos  
- **Data**: 1,500 labeled training videos (400 collisions, 350 near-misses, 750 normal) + 1,344 test videos  
- **Annotations**:  
  - `event_type`: Collision / Near-miss / Normal  
  - `alert_time`: Earliest time a potential accident can be predicted  
  - `event_time`: Time of the actual incident  
- **Evaluation Metric**: Mean Average Precision (mAP) at 500ms, 1000ms, and 1500ms before the event  
- **Prizes**:  
  - 🥇 Trip to Portugal (up to $5,000)  
  - 🥈🥉 Recognition via blog & CVPR DriveX Workshop  
- **Host**: Nexar