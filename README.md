# 🇳🇵 Nepal Federal Election Prediction using Machine Learning

This project predicts Nepal Federal Parliament election outcomes using Machine Learning and historical election data.

The model analyzes past election results and estimates future seat distribution using probabilistic simulation and statistical learning techniques.

---

## 📊 Project Overview

This project uses official Nepal Federal Election data from:

- 2017 Federal Election
- 2022 Federal Election
- All 165 FPTP constituencies

The objective is to predict:

- Winning party per constituency
- Win probability per constituency
- National seat distribution forecast
- Uncertainty ranges using simulation

---

## 🧠 Machine Learning Model

Model used:

- Algorithm: Random Forest Classifier
- Calibration: CalibratedClassifierCV
- Simulation: Monte Carlo Simulation (5000 runs)

Features used:

- Previous election winner
- Party transition patterns
- Party historical strength
- Constituency stability indicator

The model produces probabilistic predictions rather than deterministic guesses.

---

## 📈 Forecast Results (Predicted Seat Distribution)

| Party | Predicted Seats |
|------|----------------|
| Congress | ~49 |
| CPN (UML) | ~41 |
| Maoist Centre | ~14 |
| Unified Socialist | ~10 |
| RPP | ~9 |
| PSP-Nepal | ~8 |
| RSP | ~7 |
| Independent | ~6 |
| Others | Remaining |

Total seats: 165

---

## 📊 Visualization

Seat forecast generated using Machine Learning model:

![Seat Forecast](seat_forecast.png)

---

## 📁 Project Structure
