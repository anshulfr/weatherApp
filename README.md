# Weather App

A simple web application that retrieves the current weather data for a given location and displays it on the screen.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/your-repo.git`
2. Install dependencies: `npm install`
3. Set up environment variables: Create a `.env` file with the following contents:
```
/node_modules/
.env
API_KEY=0806d34c8dfcd028a68592ab149fa9e4
```
Replace `your_api_key_here` with your API key for the OpenWeatherMap API.
4. Start the server: `node index.js`
5. Open a web browser and go to `http://localhost:3000`

## Usage

Enter the name of a city or a ZIP code in the search box and click "Search". The app will display the current weather data for that location.

## Technologies Used

- Node.js
- Express
- EJS
- Bootstrap
- OpenWeatherMap API

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
