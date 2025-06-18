# -DATA-PIPELINE-DEVELOPMENT

"COMPANY":CODETECH IT SOLUTIONS

"NAME":G NAVEEN 

"INTERN ID": 

"DOMAIN":DATA SCIENCE 

"DURATION": WEEKS

"MENTOR":NEELA SANTOSH


 What is a Data Pipeline?
A data pipeline is a workflow that automates the process of collecting data, processing it, and delivering it to a storage system such as a database or a data warehouse. It is essential for analytics, machine learning, reporting, and other data-related tasks. A well-designed data pipeline ensures that data is reliable, consistent, and available when needed.
Data pipeline development involves writing code and setting up tools that perform three main tasks — Extraction, Transformation, and Loading (ETL).

The ETL process includes following three steps 

Extract
This is the first step in a data pipeline, where raw data is collected from different sources. These sources can include databases, CSV files, Excel sheets, APIs, or even web scraping. For example, in Python, the pandas library can be used to load data from CSV files using pd.read_csv().

Transform
Once the data is extracted, it often needs to be cleaned or modified to make it usable. This step includes handling missing values, converting data types, removing duplicates, and encoding categorical variables. More complex transformations may involve feature engineering for machine learning models.

Load
After transformation, the clean data is stored in a new location, such as a relational database (like MySQL), a data warehouse (like BigQuery), or simply a new CSV file. This data is now ready for reporting, analysis, or model training

The importance of data pipeline development :

 Why is it Important?
Data pipeline development ensures efficiency, scalability, and reliability in handling data. It saves time and reduces human error by automating repetitive tasks. In industries like finance, healthcare, and e-commerce, data pipelines are essential for real-time analytics and decision-making

Conclusion:

In the era of digital transformation, data has become the new oil. Every organization, regardless of its size or industry, deals with a massive amount of data daily. But raw data is often unstructured, inconsistent, or incomplete. Before it can be used for analysis, reporting, or machine learning, it must go through a structured process of cleaning, transformation, and storage. This is where Data Pipeline Development comes into play.
Data pipeline development is a foundational skill in data science and engineering. It allows raw data to be transformed into clean, structured, and meaningful information. With the help of Python and modern tools, even beginners can start building efficient pipelines for personal projects, internships, or professional applications.


I used the following raw data which consists of columns: age, gender, salary, and purchased.

data = {
    'age': [25, 30, 35, 40, None],
    'gender': ['Male', 'Female', None, 'Male', None],
    'salary': [50000, 60000, 70000, None, 40000],
    'purchased': ['No', 'Yes', 'Yes', 'No', 'Yes']
}


In this data the missing values are filled in the following criteria: 

For the age column, replace missing values with the average of the existing ages.

For gender, fill missing values with the most frequent value (mode). If 'Male' appears the most, it's used.

For salary, fill missing values with the average salary.



Encoding the categorical data:

LabelEncoder() creates an object to convert categories to numbers.

fit_transform() maps 'Male' to 1, 'Female' to 0, etc.


StandardScaler() will scale numeric values to have:

Mean = 0

Standard deviation = 1

Saves the cleaned and processed DataFrame to a file named complete_output.csv.

Here is the output:

![Image](https://github.com/user-attachments/assets/14a3c9a4-ca0c-46d2-949b-46bfec40035b)





