# Betting Inefficiencies in Premier League Odds

**Advanced Python Programming Project** | *Bocconi University, Winter 2024*

---

## Overview

This repository presents an in-depth analysis of inefficiencies in the Premier League betting market across 19 seasons (2005–2024). Using historical odds and match data from multiple bookmakers, we evaluate whether certain strategies can consistently exploit market biases.

---

## Team Members

- Ferran García Rovira  
- Anna Katharina Schnabel  
- Andrei Arin Pacuretu  
- David Ponti Pascual  
- Florian Gaszner  

---

## Main Goals

- Evaluate the efficiency of Premier League betting odds.  
- Explore different betting strategies and their profitability.  
- Identify and test for structural biases (home advantage, promoted teams, sentiment).  

---

## Methodology

- Data cleaning and preprocessing of match statistics and odds (2005–2024).
- Calculation of average bookmaker odds and implied probabilities.
- Construction of betting signals and result tracking.
- Monte Carlo simulations to assess whether strategies outperform chance.
  
---

## Key Results

- **Betting on home teams**: Negative long-term returns (–2.44% avg.)
- **Betting against promoted teams (away)**: Slightly profitable (+2.45%)
- **Sentiment-based strategy (based on attendance differentials)**: Initially promising, but unstable post-2013

---

## How to Run This Project

### Prerequisites

You must have **Python 3.9+** installed.

---

### 1. Clone the repository

```bash
git clone https://github.com/ferrangarciarovira/Premier-League-Betting-Analysis.git
cd Premier-League-Betting-Analysis
