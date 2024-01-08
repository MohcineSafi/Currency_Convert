# Currency Converter

This is a simple currency converter web application that allows users to convert amounts between different currencies. The application uses the ExchangeRate-API to fetch real-time exchange rates.

## Features

- **Currency Conversion:** Convert an amount from one currency to another.
- **Currency Selection:** Choose the currencies to convert between using dropdown menus.
- **Exchange Rate Display:** View the exchange rate and converted amount.
- **Currency Flag Icons:** Display flags of the selected currencies.

## Technologies Used

- **HTML:** Structuring the web page.
- **CSS:** Styling the user interface.
- **JavaScript:** Handling user interactions and making API requests.
- **ExchangeRate-API:** Fetching real-time exchange rates.

## Usage

1. Open `index.html` in a web browser.
2. Enter the amount you want to convert.
3. Select the source and target currencies using the dropdown menus.
4. Click the "Get Exchange Rate" button to calculate and display the converted amount.
5. The exchange rate and converted amount will be shown below the button.

## Files and Structure

- **index.html:** The main HTML file containing the structure of the web page.
- **style.css:** The CSS file for styling the web page.
- **index.js:** The JavaScript file for handling user interactions and making API requests.
- **countries.js:** A file providing a list of country codes and corresponding flags.

## Setup

No specific setup is required. Just open the `index.html` file in a web browser to use the currency converter.

## API Key

Ensure you replace `[YOUR_KEY]` in the `index.js` file with your ExchangeRate-API key. You can obtain a free key by signing up on [ExchangeRate-API](https://www.exchangerate-api.com/).

```javascript
const response = await fetch(`https://v6.exchangerate-api.com/v6/[YOUR_KEY]/latest/${fromCur.value}`);
```

## Credits

- Flag icons provided by [flagcdn.com](https://flagcdn.com/).
- Font: [Poppins](https://fonts.google.com/specimen/Poppins) from Google Fonts.
- Currency data: [ExchangeRate-API](https://www.exchangerate-api.com/).