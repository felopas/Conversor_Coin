💰 Currency Converter with Tkinter
This project is a simple Currency Converter built with Python and the tkinter library for the graphical user interface. It fetches real-time exchange rates from an external API, allowing users to convert a value between different currencies.

🚀 Features
Intuitive GUI: A clean and straightforward interface for a pleasant user experience.

Real-Time Conversion: Fetches the latest exchange rates from the ExchangeRate-API to ensure accuracy.

Error Handling: Manages common errors, such as invalid data input, internet connection issues, or API failures.

Selectable Currencies: Allows you to choose the source and target currencies from a predefined list.

🛠️ How to Use
1. Get an API Key
The code uses the ExchangeRate-API. You will need to sign up (the free plan is sufficient) and get your API key.

2. Configure the Code
Open the currency_converter.py file and replace "YOUR_API_KEY_HERE" in the line api_key = "YOUR_API_KEY_HERE" with your actual API key.

3. Install Dependencies
You need the requests library to make the API calls. Install it using pip:

Bash

pip install requests
4. Run the Application
Execute the Python script from your terminal:

Bash

python currency_converter.py
5. Use the Interface
Enter the amount you want to convert in the text field.

Select the source currency ("From:") and the target currency ("To:") from the dropdown lists.

Click the "Convert" button. The result will appear at the bottom of the window.
