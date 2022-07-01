# GitHub_Upload_Module_2_Challenge_Vivian_Yu

## Loan Qualifier Application

This application prompts the user with a series of questions regarding his or her credit score, debt, income, and desired loan amount to determine whether the user qualifies for certain loans. It will match the user to potential banks willing to underwrite the loans. It will ask the user to save the qualifying loans as a new CSV file.

## Technologies

This application uses Python 3.7 and the Fire and Questionary packages to filter through bank data to match the user to qualifying loans using debt_to_income ratio and loan-to_value ratio calculations.


---

## Installation Guide

Ensure Python packages are installed.
```sh
pip install fire
pip install questionary
```

Import libraries needed to perform the app functions.
```sh
import sys
import fire
import questionary
from pathlib import Path
```
---

## Usage

This application will ask the user questions about their financial data and perform financial calculations to see whether they meet the loan qualification criteria. The criteria is based on credit score, debt-to-income ratio, loan amount, and loan-to-value ratio.

<img width="428" alt="image" src="https://user-images.githubusercontent.com/107157533/176812040-13d35939-7c17-485f-ad65-bc39e34fcb70.png">

The app will ask for the file path to the banking data CSV file to perform its calculations.

<img width="526" alt="image" src="https://user-images.githubusercontent.com/107157533/176812418-965af512-af62-4193-b42f-267cba160d20.png">

It will then ask the user to enter their financial data. Example: User X inputs his data and qualifies for 14 loans. He is then prompted to save the file.

<img width="538" alt="FINAL SCREENSHOT" src="https://user-images.githubusercontent.com/107157533/176810938-5db867c5-a270-41d2-aece-f9e5e3a3128c.png">


---

## Contributors

Vivian Yu - vyu@terpmail.umd.edu
---

## License

Columbia Engineering FinTech Bootcamp
