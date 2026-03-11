# Hospital Admission Records Analysis

## Team Members
- Omar Allaham
- Hussam Rabaa

## Project Overview
This project prepares a reproducible Python environment for analyzing hospital admission records for a regional health authority. It ensures that all team members can install the same dependencies and run the project consistently for data analysis and validation.

## Data Sources
This project uses hospital admission data provided by a regional health authority.

Data is not tracked in this repository. See the setup instructions below for how to obtain and place the data files before running any analysis.

Expected raw data location:
data/raw/admissions.csv

## Setup Instructions

Clone the repository:

```bash
git clone https://github.com/LevelUp-Applied-AI/m1-l1-git-workflows-omaromar03.git
cd m1-l1-git-workflows-omaromar03
source .venv/bin/activate
pip install -r requirements.txt
python test_environment.py
python -m venv .venv