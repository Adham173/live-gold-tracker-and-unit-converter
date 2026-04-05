# Real-Time Gold & Currency Converter

### Project Overview
This is a functional financial tool that interfaces with external APIs to fetch live market data. It allows users to track the current price of gold and perform multi-currency conversions using real-time exchange rates.

### Technical Implementation
* **API Integration:** Utilizes the Frankfurter API for currency exchange and GoldAPI for precious metal spot prices.
* **JSON Parsing:** Handles dynamic data retrieval and parsing to extract specific price points.
* **Error Handling:** Includes logic to manage API connection states and invalid user inputs.

### How it Works
1. The script sends a GET request to the financial data providers.
2. It parses the returned JSON objects to find the `price` or `rate` key.
3. It performs the conversion math based on the user's requested amount.
