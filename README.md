# Analyze Death Age Difference of Right vs Left Handers

This project investigates the myth that left-handed individuals die earlier than right-handed individuals.  
We analyzed age-at-death distributions combined with changing rates of reported left-handedness over time, 
using Bayesian statistics and data visualization techniques.

## 📊 Features
- Data cleaning and preprocessing
- Functions developed:
  - `P_lh_given_A(age, year)`: Probability of being left-handed at a given age in a specific year (LH = Left-Handed)
  - `P_lh(death_data, year)`: Overall probability of left-handedness (LH) in the death dataset
  - `P_A_given_lh()`: Probability of age at death given LH
  - `P_A_given_rh()`: Probability of age at death given RH (Right-Handed)
- Plots showing probability distributions and mean age at death comparisons

## 📁 Files
- `Industrial_training_report.pdf`: Complete project report
