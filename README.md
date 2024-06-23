# Tariff Recommendation Project

## Project Overview

The goal of this project is to develop a machine learning model to recommend one of two tariffs, "Smart" or "Ultra," for customers of the mobile operator "Megaline." The company has identified that many clients are still using outdated tariffs, and they aim to analyze customer behavior to suggest a new tariff plan. The data provided includes customer behavior for those who have already switched to these new tariffs. Your task is to build a classification model that maximizes accuracy, achieving at least 0.75 on the test set.

## Data Description

Each row in the dataset represents one user’s behavior over a month. The columns are:

- **calls** — number of calls
- **minutes** — total call duration in minutes
- **messages** — number of SMS messages
- **mb_used** — data usage in megabytes
- **is_ultra** — tariff used during the month ("Ultra" — 1, "Smart" — 0)
