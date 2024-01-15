# Currency Converter App

This Currency Converter App is a user-friendly web application developed using React. It facilitates quick and accurate currency conversions by fetching real-time exchange rates from an API.

## Features

- Fetches currency exchange rates from [Currency API](https://github.com/fawazahmed0/currency-api).
- Allows users to input the amount for conversion.
- Provides a dropdown to select source and target currencies.
- Supports easy swapping of source and target currencies.
- Displays the converted amount instantly.

## How to Use

### Prerequisites

- Ensure Node.js is installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AmanKumarSinhaGitHub/Live-Currency-Convertor.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Live-Currency-Convertor
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

### Usage

1. Run the application:

   ```bash
   npm run dev
   ```

2. Open your browser and go to [http://localhost:5173](http://localhost:5173).

3. Enter the amount, select the source and target currencies, and click the "Convert" button.

4. Optionally, use the "Swap" button to switch the source and target currencies.

## Code Structure

### `App.js`

- Main component rendering the entire application.
- Manages state for amount, source currency, target currency, and converted amount.
- Utilizes the `useCurrencyInfo` custom hook to fetch currency exchange rates.

### `useCurrencyInfo.js`

- Custom hook to fetch real-time currency exchange rates from an external API.
- Utilizes the `fetch` function to retrieve data and update the component state.

### `InputBox.js`

- Reusable component for input fields.
- Accepts props such as label, amount, currency options, and handles user input for amount and currency selection.

## Contribution Guidelines

Feel free to contribute to the project by submitting issues or pull requests. Your contributions are highly appreciated!

## Getting Exchange Rates

The app fetches real-time exchange rates from the [Currency API](https://github.com/fawazahmed0/currency-api), ensuring accurate and up-to-date information.

Happy converting! 💰🔄