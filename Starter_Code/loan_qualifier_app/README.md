# Loan Qualifying Application

This application takes a users information (credit score, monthly debt, monthly income, desired loan amount, and home value) and determines which loans the user is qualified to apply for. It is meant to do the loan research work for the user.

---

## Technologies

This application is written in Python. The Python libraries used are [Python Fire](https://github.com/google/python-fire) and [Questionary](https://github.com/tmbo/questionary). We used Fire so we could allow users to use a CLI and we used Questionary to allow users to have a more friendly and interactive experience.

---

## Installation Guide

Before running Fire and Questionary, you will need to install them first. 

To install Fire, go to your terminal and run the following command:

`pip install fire`

To install Questionary, go to your terminal and run the following command:

`pip install questionary`

---

## Usage

When first launching the application, the first question will be the file path to the rate sheet of all the loans. (The yellow is what the user will have typed).

![File Path](../../../file%20path.png)

After asking for the file path, the application will ask a series of questions to filter out the loans the user qualifies for. 

![Questions](../../../questions.png)

The application will then tell you your monthly debt to income ration and the loan to value ratio and how many loans you qualify for based on the information the user entered above.

![Summary](../../../summary.png)

Finally the app will ask if the user wants to save the list of qualifying loans in a spreadsheet. It will then let the user know if the file has been saved or not. 

---

## Contributors

Initially set up by Rice University FinTech Bootcamp.

Edited by Brittanie Polasek.

---

## License

MIT
