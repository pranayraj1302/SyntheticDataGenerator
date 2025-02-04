Import Necessary Libraries

The required modules (Faker, pandas, randint) are imported to generate fake data and store it in a structured format.
Initialize Faker Instance

An instance of the Faker class is created to generate different types of fake data.
Define a Function to Generate Fake Data

A function is written that takes a number (n) as input, specifying how many records to generate.
A loop runs n times, creating a dictionary for each fake user with randomly generated values like ID, name, address, phone number, and company.
These dictionaries are collected into a list and converted into a Pandas DataFrame (a structured table-like format).
Call the Function to Generate Data

The function is executed with a specified number of records (e.g., 10).
The generated fake data is stored in a variable.
Display the Generated Data

The data is printed in tabular form so the user can see the fake records.
Save the Data to a CSV File

The generated dataset is saved as a .csv file, making it easy to access and use later.
