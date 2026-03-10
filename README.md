# Hospital Admission Records Analysis

> Lab 1 project for configuring a reproducible Python environment for analyzing hospital admission records.

---

## Project Overview

This project prepares a shared Python environment for analyzing hospital admission data for a regional health authority.  
It ensures that all team members can install the same dependencies and run the project consistently.

---

## Setup Instructions

```bash
python -m venv .venv

# Activate — choose the command for your OS:
# Mac / Linux:      source .venv/bin/activate
# Windows Git Bash: source .venv/Scripts/activate
# Windows CMD:      .venv\Scripts\activate.bat
# Windows PowerShell: .venv\Scripts\Activate.ps1

pip install -r requirements.txt
python test_environment.py    # should print "Environment OK"