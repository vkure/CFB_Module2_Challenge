# *Loan Qualifier Application*

This is a python command-line interface application that identfies qualifying loans given a set of user inputs.  The inputs are based on the borrower and potential home purchase.  The application works by taking in a 'daily rate sheet' of loan criteria from various loan providers.  The resulting output is a list of qualifying loans and will be saved in a CSV file specified by the user.

---

## Technologies

The application is written in Python 3.8 with support from the following packages:  

*[fire] (https://github.com/google/python-fire) - CLI
*[questionary] (https://github.com/tumbo/questionary) - user prompts


## Installation Guide

Before running the app, first install the following dependencies.

```python
pip install fire
pip install questionary
```

## Usage

To use the loan qualifier application, pls clone the repository and run the **app.py** with:
```python
python app.py
```

Upon launching the application, you will be greeted with the following prompts.  Pls respond accordingly.

![Loan Qualifier Prompts](Images/Loan_Qualifier_App.png)

## Contributors
Vishnu Kurella, vishnu.kurella@gmail.com

## License
VK.LQA 2021

