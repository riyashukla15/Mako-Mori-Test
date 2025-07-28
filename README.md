# 🎥 Mako Mori Test: Analyzing Gender Representation in Films

## Overview
This project applies data analysis techniques to explore how modern films represent women using the **Mako Mori Test** — a simple yet powerful measure of female narrative agency in cinema. The goal is to examine whether high-rated and popular movies offer female characters independent storylines or merely portray them as supporting roles.

---

## Problem Statement
While watching various films, I noticed a recurring trend: female characters often exist only to support the male protagonist. This project investigates:
- How many movies pass the Mako Mori Test?
- Is there a correlation between passing the test and a film’s **IMDB rating**, **genre**, or **box office success**?

---

## Methodology
1. **Data Cleaning & Preparation**:
   - Removed duplicates and null values.
   - Used `gender-guesser` and other logic to identify gender of lead characters.
   - Manually verified Mako Mori test results for a subset of movies.

2. **Analysis & Visualization**:
   - Grouped movies by test result (Pass/Fail).
   - Compared average ratings and revenue.
   - Visualized genre-wise pass rates.

3. **Insights Extraction**:
   - Focused on identifying patterns across successful movies and gender-based representation.

---

## Key Findings
- A large percentage of top-rated or blockbuster films **fail** the Mako Mori Test.
- Films passing the test tend to have stronger critical reception in genres like **Drama** and **Biopic**.
- Action and Adventure films show the **lowest pass rate**.

---

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- CSV dataset containing movie metadata

