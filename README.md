# Health Services Analysis

This project generates synthetic data for health services and performs various analyses to investigate waiting times, risks, and outcomes associated with surgical treatments.

## Files

- `generate_data.py`: Script to generate synthetic health services data.
- `analyze_data.py`: Script to analyze the synthetic data.
- `synthetic_health_services_data.csv`: Generated synthetic data.
- `factors_associated_with_waiting_times.txt`: Regression analysis results on factors associated with waiting times.
- `factors_associated_with_waiting_times.png`: Bar plot of factors associated with waiting times.
- `probability_within_recommended_time.txt`: Probability of undergoing elective surgery within the recommended time.
- `probability_within_recommended_time.png`: Bar plot of probability of undergoing elective surgery within the recommended time.
- `procedure_waiting_times.csv`: Average waiting times for different types of procedures.
- `procedure_waiting_times.png`: Bar plot of the effect of procedure type on waiting time.
- `effect_of_delay.png`: Plot showing the effect of scheduling delays on waiting times.
- `unplanned_emergency_risk.csv`: Risk of unplanned emergency surgery based on waiting times.
- `unplanned_emergency_risk.png`: Line plot of the risk of unplanned emergency surgery.
- `death_risk.csv`: Risk of death associated with delayed surgical treatment.
- `death_risk.png`: Line plot of the risk of death associated with delayed surgical treatment.

## Usage

1. Run `generate_data.py` to generate the synthetic dataset.
2. Run `analyze_data.py` to perform the analysis and generate results.
3. Review the generated files for insights and visualization.

## Requirements

- numpy
- pandas
- statsmodels
- seaborn
- matplotlib

## Installation

Install the required packages using:

```bash
pip install -r requirements.txt
