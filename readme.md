Loan approval prediction - kaggle competition - final analisis predictivo

https://www.kaggle.com/competitions/playground-series-s4e10

dataset description:
person_age: The applicant's age.
person_income: How much money the applicant makes per year.
person_home_ownership: Whether the applicant owns a home or not.
person_emp_length: How many years the applicant has been working.
loan_intent: The reason the applicant needs the loan.
loan_grade: A score showing how reliable the applicant is in paying back loans.
loan_amnt: The amount of money the applicant wants to borrow.
loan_int_rate: The interest rate charged on the loan.
loan_percent_income: What percentage of the applicant's income will go to loan payments.
cb_person_default_on_file: Shows if the applicant has ever failed to pay back a loan.
cb_person_cred_hist_length: How long the applicant has had a credit history
loan_status: Shows if the loan is approved or rejected


### Orden de corrida:
Primero correr EDA_features.ipynb para realizar el EDA y feature engineering
Luego, correr cualquier modelo para entrenarlo y generar predicciones. (Modelo de mejor rendimiento y usado para el final, LightGBM)