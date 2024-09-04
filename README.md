Currency Converter

Overview
The Currency Converter is a web application that allows users to convert an amount of money from one currency to another. It fetches the latest exchange rates and provides a user-friendly interface for making currency conversions.

Features
- Real-time Exchange Rates: Fetches the latest exchange rates from an API.
- Currency Selection: Users can select both the source and target currencies.
- Simple Interface: Clean and easy-to-use UI for quick conversions.
- Responsive Design: Optimized for desktop and mobile devices.

 Getting Started
 Prerequisites
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (comes with Node.js)

 Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/currency-converter.git
    cd currency-converter
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up the API:

   Replace `'your api url'` in `server.js` with the actual API URL that provides currency exchange rates.

4. Run the application:

    ```bash
    npm start
    ```

5. Access the app:
Open your browser and go to `http://localhost:4500`.

 File Structure
- `index.html`: Main HTML file.
- `styles.css`: Stylesheet for the application.
- `script.js`: JavaScript for the client-side logic.
- `server.js`: Node.js server script for handling API requests.
- `package.json`: Configuration file for npm.
