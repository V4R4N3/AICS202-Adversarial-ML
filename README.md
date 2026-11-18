# AICS-202 Adversarial Machine Learning

**ICDFA | Course: AICS-202 | Cohort 1**

## Overview
Controlled adversarial ML security assessment covering baseline modelling, FGSM evasion, training-data poisoning, and defensive retraining using the scikit-learn digits dataset.

## Labs
| Lab | Topic | Key Result |
|-----|-------|------------|
| Lab 01 | Baseline model + threat model | 96.22% clean accuracy |
| Lab 02 | FGSM evasion | Accuracy drops to 20.4% at ε=0.18 |
| Lab 03 | Training-data poisoning | 93.3% accuracy at 20% label corruption |
| Lab 04 | Defensive retraining | Augmented model performs worse under adaptive attack |

## How to run
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```
Open notebooks sequentially: Lab01 → Lab02 → Lab03 → Lab04.
Restart kernel and Run All cells before reviewing results.

## Environment
- Python 3.10+
- numpy, scikit-learn, matplotlib, notebook
- Dataset: scikit-learn load_digits() — no internet required
- SEED = 42 for all experiments
