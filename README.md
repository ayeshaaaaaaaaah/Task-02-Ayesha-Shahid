# DecodeLabs AI Internship - Project 2
## Supervised Machine Learning Classifier (Iris Benchmark)

### 🚀 Milestone Overview
This repository contains my submission for **Project 2** of the DecodeLabs Industrial Training Track. This phase marks the transition from deterministic rule-based logic gates into true Supervised Machine Learning and statistical pattern recognition.

### ⚙️ Pipeline Architecture (IPO Model)
* **Input Layer:** Direct programmatic ingestion of the official **Iris Benchmark Dataset** (150 balanced samples, 4 distinct dimensional measurements).
* **Process Layer - Feature Scaling:** Implemented mathematical normalizations via `StandardScaler` to force features into a consistent scale (Mean = 0, Variance = 1), preventing algorithmic distance bias.
* **Process Layer - Structural Split:** Shuffled and partitioned data into an **80% Training Set** for pattern recognition and a **20% Test Set** for validation to guarantee zero data leakage.
* **Process Layer - Model Training:** Applied the **K-Nearest Neighbors (KNN)** classification algorithm to map geometric spatial proximities and derive native decision boundaries without manual heuristics.
* **Output Layer:** Evaluated model precision using a comprehensive Performance Confusion Matrix, tracking Test Accuracy and F1-Scores.
