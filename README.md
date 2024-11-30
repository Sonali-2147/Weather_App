Dynamic Weather Website 🌤️

This project is a dynamic weather application built using HTML, CSS, and Node.js. It fetches real-time weather data from the OpenWeather API and provides users with current weather conditions, forecasts, and additional information like the current day, date, and time.

Weather App Deployed on Netlify: https://sonalik.netlify.app/

🌟 Features

User-friendly interface for entering location details.
Real-time weather data using the OpenWeather API.
Displays:
Current weather conditions (temperature, humidity, wind speed, etc.).
Weather forecasts.
Current day, date, and time.
Backend built using Node.js and Express.js for handling API requests and server-side logic.

🛠️ Technologies Used

Frontend: HTML, CSS
Backend: Node.js, Express.js
API: OpenWeather API

📂 Project Structure
.
├── public
│   ├── css
│   │   └── style.css         # Stylesheet for the frontend
│   └── js
│       └── script.js         # (Optional) Client-side scripts
├── views
│   ├── index.html            # Main HTML file
├── server.js                 # Entry point for Node.js server
├── package.json              # Project dependencies and scripts
└── README.md                 # Project documentation

🚀 Getting Started

Follow these instructions to set up the project locally:

Prerequisites

Node.js installed on your machine
An OpenWeather API key. Sign up at OpenWeather to get your free API key.

Installation
Clone the repository:

git clone https://github.com/your-username/dynamic-weather-website.git
cd dynamic-weather-website
Install dependencies:

npm install
Create a .env file in the root directory and add your OpenWeather API key:

API_KEY=your_openweather_api_key
Start the server:

node server.js
Open your browser and navigate to:

https://sonalik.netlify.app/
📸 Screenshots
Home Page

Weather Display

📈 Future Enhancements
Add support for multiple languages.
Provide additional weather data like UV index, air quality, etc.
Improve UI/UX with animations and more interactive elements.
🤝 Contributing
Contributions are welcome! Feel free to submit a pull request or report any issues.
