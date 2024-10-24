# World Currencies Viewer

## Overview

World Currencies Viewer is a simple, responsive web application that displays information about currencies from around the world. It allows users to view currency codes, country names, and currency symbols, as well as search for specific countries.

## Features

- Display of world currencies with their respective country names and symbols
- Real-time search functionality to filter countries
- Responsive design that works on desktop and mobile devices
- Data fetched from an up-to-date GitHub repository

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript

## Live Demo

[https://world-currencies-api.vercel.app/example](https://world-currencies-api.vercel.app/example)

## JSON URL

The currency data can be accessed directly via this URL:

```
https://world-currencies-api.vercel.app/world-currencies.json
```

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/1dev-hridoy/world-currencies-api.git
   ```

2. Navigate to the project directory:
   ```
   cd world-currencies-api
   ```

3. Open the `index.html` file in your web browser.

That's it! The application should now be running locally on your machine.

## Installation

This project doesn't require any dependencies to be installed as it uses Tailwind CSS via CDN. However, if you want to modify the project and use a local version of Tailwind CSS, you would need to install Node.js and npm, then run:

```
npm install tailwindcss
```

## Usage

- When you open the application, you'll see a list of all world currencies.
- Use the search bar at the top of the page to filter countries by name.
- The list will update in real-time as you type in the search bar.
- Each currency entry displays the country name, currency code, and currency symbol.
- The layout is responsive and will adjust based on your device's screen size.

## Data Source

The currency data is fetched from the following GitHub repository:
[https://github.com/1dev-hridoy/world-currencies-api](https://github.com/1dev-hridoy/world-currencies-api)

The JSON structure for each currency entry is as follows:

```json
{
  "CurrencyCode": {
    "name": "Country Name",
    "symbol": "Currency Symbol"
  }
}
```

For example:

```json
{
  "USD": {
    "name": "United States",
    "symbol": "$"
  }
}
```

## Contributing

Contributions to improve the World Currencies Viewer are welcome. Here are some ways you can contribute:

1. Report bugs
2. Suggest new features
3. Submit pull requests with improvements

Please make sure to update tests as appropriate.

## Potential Improvements

- Add sorting functionality (e.g., sort by country name or currency code)
- Implement pagination for better performance with large datasets
- Add more details for each currency (e.g., exchange rates)
- Create a dark mode option
- Implement a backend API for more dynamic data handling

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or concerns, please open an issue on the GitHub repository or contact the maintainer:

- GitHub: [@1dev-hridoy](https://github.com/1dev-hridoy)

---
