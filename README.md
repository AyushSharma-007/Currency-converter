# Currency-converter
This will convert the currency 
Understanding the Requirements
To create a currency converter, we'll need:

A library to fetch real-time exchange rates: We'll use the requests library to make API calls to a currency exchange service.
A user interface: We can use a simple command-line interface or a graphical user interface (GUI) using libraries like Tkinter.
Data handling: We'll parse the API response to extract the required exchange rates.
Choosing a Currency Exchange API
Many free and paid APIs are available. Popular options include:

Fixer.io: Provides historical and latest exchange rates.
Open Exchange Rates: Offers free and paid plans with various features.
Alpha Vantage: Provides financial data, including currency exchange rates.
For this example, we'll use Fixer.io.
Import necessary libraries: requests for making API calls and json for parsing the response.
Define functions:
get_exchange_rate: Fetches the exchange rate from Fixer.io based on the provided base and target currencies.
convert_currency: Calculates the converted amount using the fetched exchange rate.
main: Handles user input and calls the conversion function.
User input: Prompts the user for base currency, target currency, and the amount to convert.
Conversion: Calls the convert_currency function and prints the result.
