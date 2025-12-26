# Pulse SaaS Review Scraper

## Overview
A production-grade scraper built to extract product reviews from G2, Capterra, and TrustRadius.

## 🌟 Novelty & Key Features
- **Sentiment Analysis:** Every review is processed through an NLP layer (TextBlob) to categorize customer sentiment as Positive, Negative, or Neutral.
- **Data Integrity:** Built using Pydantic models to ensure all JSON output is strictly validated and type-safe.
- **Bonus Source:** Fully integrated TrustRadius as a third specialized SaaS source.

## 🛠️ Setup & Running
1. Open Terminal and navigate to the folder:
   `cd ~/Desktop/Pulse_assignment`
2. Install dependencies:
   `pip3 install -r requirements.txt`
3. Execute the script:
   `python3 main.py --company "Slack" --start "2024-01-01" --end "2024-12-31" --source "G2"`

## Output
The results are saved automatically in `output.json`.
