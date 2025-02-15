Objective: Download Data from Public APIs.

Instructions:
Search for information in public APIs (i.e. Twitter, NewsAPI, Spotify, Google APIs, etc.).
Extract data and import it into a dataframe by performing a simple exploration.

Aspects to include:
Notebook detailing all the steps followed Format: A jupyter notebook must be delivered with the name “practical activity_APIS_+First_Name_+Last_Name.ipynb”.

Steps to Follow:
Selecting the API: We will choose a public API to extract data.
In this example, we will use the NewsAPI API to obtain recent news.
Registering and Obtaining the API Key: We will need to register with NewsAPI to obtain an API key.
Installing Libraries: We will install the necessary libraries to make HTTP requests and manipulate data.
Data Extraction: We will make a request to the API to obtain data.
Importing to a DataFrame: We will convert the obtained data into a Pandas DataFrame.
Simple Exploration: We will perform a basic exploration of the data.

Code Explanation:
Installing Libraries: We install requests to make HTTP requests and pandas to manipulate the data.
Importing Libraries: We import the necessary libraries.
API Configuration: We define the API URL and the necessary parameters, including the API key.
Request to the API: We make a GET request to the API and check if the response is successful (code 200).
Importing to a DataFrame: We convert the obtained data into a Pandas DataFrame.
Simple Exploration: We display the first rows of the DataFrame, general information and descriptive statistics.
Saving the DataFrame: Optionally, we save the data in a CSV file.
