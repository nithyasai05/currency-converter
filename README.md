#### Currency Converter:
   *A simple web-based currency converter that allows users to convert amounts from one currency to another using real-time exchange rates. 
   *The project fetches data from a public API and dynamically populates the currency options for conversion.

Features:
  1.Converts amounts between different currencies using the latest exchange rates.
  2.Dynamic population of available currencies via API.
  3.Displays the conversion result immediately on button click.
  
Technologies Used:
      HTML5: For the structure of the webpage.
      CSS3: For styling the currency converter interface.
      JavaScript (ES6): For functionality, including fetching exchange rates from an API and performing the conversion.

How It Works:

* The page loads with two dropdown menus (From and To) that list available currencies. These are fetched dynamically from the Currency API.
* The user selects the currencies they want to convert between.
* The user inputs the amount they want to convert.
* When the "Convert" button is clicked, the app fetches the conversion rate, performs the calculation, and displays the result.

This project is completely frontend-based, so you can simply open the HTML file in your preferred browser.

HTML Structure:
 * The main structure consists of a form with two dropdowns (for selecting currencies), an input for the amount, and a button for conversion.
 * 
CSS Styling:
 * The webpage is styled using CSS embedded within the HTML file. The main design elements include a centered box on the page with a shadow, a blue background, and button hover effects.

JavaScript Logic:
 * The currency list is fetched from the API and populated into the dropdowns.
 * The convertcurrency function handles the conversion logic, fetching real-time currency data and calculating the conversion result based on the selected currencies and the input amount.
