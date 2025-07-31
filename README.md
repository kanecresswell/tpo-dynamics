# TPO Shape Analyzer

A Python-based tool for analyzing and visualizing Time Price Opportunity (TPO) charts for ES futures. This project is designed to support robust, explainable classification of market profile shapes using scientific and statistical methods.

## 🔍 Purpose

This tool helps identify and classify daily market profile structures such as:

- Normal Day
- Normal Variation Day
- Trend Day
- Neutral Day
- Unknown (fallback)

It also provides visual validation through side-by-side plots:
- 📊 TPO count histogram
- 🔤 TPO letters by time bracket

## 📈 Features

- Clean TPO chart aligned to 30-minute time brackets (A–M)
- Histogram of TPO counts for structural insight
- Key level annotations: POC, VAH, VAL, Open, Last
- Classification logic based on POC position, value area width, and open/close dynamics
- Modular design for future enhancements (e.g. single prints, poor highs/lows, volume overlays)

## 🛠️ Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
