<div align="center">

# 🚀 AI Campaign Optimizer
### Intelligent Customer Segmentation, Predictive Analytics & AI-Powered Campaign Generation

<p align="center">
<img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Streamlit-Interactive-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ScikitLearn-ML-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Google-Gemini_AI-4285F4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Plotly-Visualization-purple?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-ProductionReady-success?style=for-the-badge"/>
</p>

<p align="center">
AI-powered marketing intelligence platform that combines machine learning, predictive analytics, customer segmentation, and Generative AI to optimize campaigns and improve conversion rates.
</p>

</div>

---

# 📖 Overview

AI Campaign Optimizer is a complete intelligent marketing analytics platform that transforms raw customer data into actionable business insights.

The application combines:

- Customer Segmentation
- Response Prediction
- Marketing Analytics
- Interactive Dashboards
- Generative AI Campaign Creation

Instead of manually analyzing spreadsheets and customer data, the platform automatically identifies high-value users and generates personalized campaigns.

---

# ✨ Core Features

## 📊 Campaign Analytics Dashboard

Track and visualize:

- Customer KPIs
- Conversion rates
- Segment distribution
- Customer activity
- Purchase trends
- Performance metrics

Interactive dashboards help identify opportunities instantly.

---

## 👥 Customer Segmentation

Uses Machine Learning clustering on:

- Recency
- Frequency
- Monetary value

Automatically groups users into:

- High Value
- Growth
- At Risk
- Dormant

Enables targeted marketing decisions.

---

## 🎯 Response Prediction Engine

Predict campaign response probability using ML.

Provides:

- Prediction confidence
- Response probability
- Top likely responders
- Accuracy metrics
- AUC score

Focus campaigns only on customers most likely to convert.

---

## ✉️ AI Campaign Generator

Generate personalized campaign content using Google Gemini AI.

Supported channels:

- Email
- SMS
- Push Notifications

Content generation adapts based on:

- Customer segment
- Behavioral data
- Purchase history
- Engagement metrics

---

## 📈 Interactive Visualization

Includes:

- KPI Cards
- Scatter plots
- Histograms
- Trend charts
- Segment analytics
- Customer drill-down

---

# 🧠 Machine Learning Workflow

```text
Raw Customer Data
        ↓
Data Processing
        ↓
Feature Engineering
        ↓
RFM Analysis
        ↓
K-Means Segmentation
        ↓
Logistic Regression
        ↓
Response Prediction
        ↓
Gemini AI
        ↓
Generated Campaign
```

---

# 🏗 System Architecture

```text

                 +----------------+
                 | Customer Data  |
                 +----------------+
                          |
                          ↓
              +----------------------+
              | Data Processing      |
              +----------------------+
                          |
                          ↓
              +----------------------+
              | Segmentation Module  |
              | KMeans Clustering    |
              +----------------------+
                          |
                          ↓
              +----------------------+
              | Prediction Engine    |
              | Logistic Regression  |
              +----------------------+
                          |
                          ↓
             +-----------------------+
             | Campaign Generator    |
             | Google Gemini API     |
             +-----------------------+
                          |
                          ↓
                 +----------------+
                 | Streamlit UI   |
                 +----------------+

```

---

# 📂 Project Structure

```bash

AI-Campaign-Optimizer/
│
├── app.py
├── generate_data.py
├── requirements.txt
├── README.md
├── .env
├── .env.example
│
├── data/
│   └── customers.csv
│
├── modules/
│   │
│   ├── data_loader.py
│   │      # loads customer dataset
│   │
│   ├── segmentation.py
│   │      # KMeans customer segmentation
│   │
│   ├── analytics.py
│   │      # KPI computation
│   │
│   ├── prediction.py
│   │      # ML prediction engine
│   │
│   └── campaign_gen.py
│          # Gemini campaign generation
│
└── assets/
       └── screenshots

```

---

# 📊 Dashboard Pages

## 1. Overview Dashboard

Displays:

- Total customers
- Average CLV
- Top segment
- Conversion rate
- Purchase trends
- Segment distribution

---

## 2. Customer Segments

Includes:

- Segment summary
- 3D RFM visualization
- Customer drill-down
- Segment filtering

---

## 3. Prediction Dashboard

Provides:

- Response probability
- Model metrics
- Customer rankings
- Probability distribution

---

## 4. Campaign Generator

Generate:

- Email campaigns
- SMS campaigns
- Push notification campaigns

Powered by Gemini AI.

---

# 🧪 ML Models Used

## Customer Segmentation

Algorithm:

```python
KMeans Clustering
```

Features:

- Recency Score
- Frequency Score
- Monetary Score

---

## Campaign Prediction

Algorithm:

```python
Logistic Regression
```

Input Features:

- Email Opens
- Total Spend
- Purchase Count
- Customer Activity

Outputs:

- Response probability
- Customer ranking

---

# ⚙ Tech Stack

### Frontend

- Streamlit

### Machine Learning

- Scikit Learn
- KMeans
- Logistic Regression

### Data Processing

- Pandas
- NumPy

### Visualization

- Plotly

### AI Integration

- Google Gemini API

### Environment

- Python
- Dotenv

---

# 📦 Installation

Clone repository:

```bash
git clone https://github.com/yourusername/AI-Campaign-Optimizer.git

cd AI-Campaign-Optimizer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 📥 Requirements

```txt
streamlit
pandas
scikit-learn
plotly
google-generativeai
python-dotenv
```

---

# 🔑 Environment Variables

Create:

```bash
.env
```

Add:

```env
GEMINI_API_KEY=your_api_key_here
```

Get Gemini API key from:

https://makersuite.google.com/

---

# ▶ Generate Dataset

Run:

```bash
python generate_data.py
```

Creates:

```bash
data/customers.csv
```

Synthetic dataset includes:

- demographics
- purchases
- engagement metrics
- response behavior
- purchase history

---

# ▶ Run Application

```bash
streamlit run app.py
```

Application starts:

```bash
http://localhost:8501
```

---

# 📸 Screenshots

Create folder:

```bash
assets/screenshots/
```

Recommended screenshots:

### Dashboard

```bash
assets/screenshots/dashboard.png
```

### Segments

```bash
assets/screenshots/segments.png
```

### Predictions

```bash
assets/screenshots/predictions.png
```

### Generator

```bash
assets/screenshots/generator.png
```

Add:

```md
## Dashboard Preview

![Dashboard](assets/screenshots/dashboard.png)

![Segments](assets/screenshots/segments.png)

![Predictions](assets/screenshots/predictions.png)

![Generator](assets/screenshots/generator.png)
```

---

# 🔥 Business Impact

Traditional marketing workflows:

❌ Generic campaigns  
❌ Manual targeting  
❌ Poor personalization  
❌ Low conversion  

AI Campaign Optimizer provides:

✅ ML-powered targeting  
✅ Predictive intelligence  
✅ Personalized campaigns  
✅ Higher conversion potential  

---

# 🚀 Future Improvements

Planned upgrades:

- CRM integration
- A/B testing engine
- Reinforcement learning optimization
- Real-time data streaming
- Multi-model comparison
- Customer lifetime forecasting
- Email automation APIs
- Multi-language campaign generation

---


# 🤝 Contributing

Contributions are welcome.

Steps:

```bash
Fork repository

Create feature branch

Commit changes

Push branch

Create Pull Request
```

---

# ⭐ Support

If you found this useful:

Give the repository a star ⭐

---

<div align="center">

Built with Machine Learning + Generative AI + Data Intelligence 🚀

</div>
