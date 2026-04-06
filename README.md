# Frequency Estimator App

A simple Streamlit app that replicates the Excel-based frequency estimator as a clean daily-use calculator.

## Run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## What it does

- Captures 22 factor scores on a 1-7 scale
- Calculates Desired Efficient Frequency using the same weighted-average logic as the Excel file
- Shows overall result and section-level averages for Marketing, Creative, and Media

## Notes

- `Reset to neutral` sets all factors to 4
- `Load sample` loads the sample scores from the workbook
- Current weights are equal across all factors, matching the uploaded Excel
