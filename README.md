
# Currency Converter

A simple currency converter web app that allows users to convert between different currencies using real-time exchange rates. The app fetches exchange rates from a public API to ensure the conversion is accurate and up-to-date.


## Features
- Convert from one currency to another.
- Display country flags beside the dropdown for a better user experience.
- Get the latest exchange rates using a real-time currency API.
- Responsive design for both desktop and mobile devices.
- Easy-to-use interface with dropdowns for selecting currencies..

## Tech Stack
- **HTML**: Structure and content of the web page.
- **CSS**: Styling the layout and making it responsive across different devices.
- **JavaScript**: Fetching exchange rates from the API, updating the UI, and handling user input.
- **API**: Fetching currency exchange data using the [Fawaz Ahmed's Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies).
## How It Works

### User Interface:
- The user enters the amount to convert in the "Enter Amount" input field.
- The user selects the currency they want to convert from and the currency they want to convert to using two dropdown menus.
- The flags corresponding to the selected currencies are displayed beside the dropdowns.

### Fetching Data:
- When the user clicks the "Get Exchange Rate" button, the app fetches real-time exchange rates using the public API hosted by [Fawaz Ahmed's Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies).
- The API returns the exchange rate between the selected currencies, and the conversion result is displayed on the screen.

### Responsive Design:
- The app layout is designed to be responsive, ensuring it looks good on devices of all screen sizes (desktops, tablets, and mobiles).
## Demo

You can check the live demo of the Currency Converter web app [here](https://imharishpatil.github.io/Currency-Converter/).



## Acknowledgements

- The currency data is fetched from the [Fawaz Ahmed's Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies).
- The flags are fetched from [FlagsAPI](https://flagsapi.com/).
- FontAwesome icons are used for the currency switcher arrow.
## License
This project is open-source and available under the MIT License.

## Contributing
If you have any suggestions or improvements for this project, feel free to fork the repository, make changes, and submit a pull request. Here's how you can contribute:

- Fork the repository.
- Create a new branch for your feature (git checkout -b feature-name).
- Commit your changes (git commit -am 'Add feature').
- Push to the branch (git push origin feature-name).
Submit a pull request.
## Contact

For any questions or inquiries, please open an issue on the GitHub repository or contact me directly.

