# 🌤️ Weather App

A simple and responsive **Weather Application built with React.js** that provides weather information based on the user's location or a searched location.

The application uses weather data APIs to retrieve current weather conditions and presents the information through a clean and interactive interface.

## ✨ Features

* 🌍 **Location-Based Weather** — Get weather information using your current geographical location.
* 🔎 **Location Search** — Search for weather information by location.
* 🌡️ **Weather Information** — View relevant weather conditions for the selected location.
* 🕐 **Live Clock** — Displays the current time within the application.
* 🌤️ **Animated Weather Icons** — Visual representation of different weather conditions.
* 📱 **Responsive Interface** — Designed to work across different screen sizes.
* ⚡ **API Integration** — Fetches weather data dynamically using Axios.
* 📍 **Geolocation Support** — Uses browser geolocation capabilities to determine the user's location.

## 🛠️ Tech Stack

| Technology                 | Purpose                           |
| -------------------------- | --------------------------------- |
| **React.js**               | Frontend application              |
| **JavaScript**             | Application logic                 |
| **Axios**                  | API requests                      |
| **React Geolocated**       | Location detection                |
| **React Animated Weather** | Animated weather visuals          |
| **React Live Clock**       | Real-time clock                   |
| **Skycons**                | Weather icons                     |
| **CSS**                    | Styling and layout                |
| **Create React App**       | Development and build environment |

## 📂 Project Structure

```text
weather-app/
│
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── ...
│
├── src/
│   ├── components/
│   ├── App.js
│   ├── index.js
│   └── ...
│
├── package.json
├── package-lock.json
├── launch.json
├── LICENSE
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* [Node.js](https://nodejs.org/)
* npm

### 1. Clone the Repository

```bash
git clone https://github.com/rishabh291202/weather-app.git
```

### 2. Navigate to the Project

```bash
cd weather-app
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm start
```

The application will start on:

```text
http://localhost:3000
```

## 📦 Available Scripts

### `npm start`

Runs the application in development mode.

### `npm test`

Runs the project's test suite.

### `npm run build`

Creates an optimized production build.

### `npm run eject`

Ejects the Create React App configuration.

> **Note:** `eject` is a one-way operation and is generally not required for normal development.

## 🔄 How It Works

1. The user opens the Weather App.
2. The application can request the user's geographical location through the browser.
3. Weather information is requested from the configured weather API.
4. Axios handles the API communication.
5. The application processes the returned weather information.
6. Weather conditions are displayed through the React interface.
7. Animated weather icons provide a visual representation of the current conditions.

## 🎯 Project Purpose

This project was created to practice and demonstrate:

* React.js development
* API integration
* Asynchronous data fetching
* Browser geolocation
* Component-based architecture
* Frontend state and UI management
* Responsive web application development

## 🔮 Future Improvements

Possible improvements include:

* [ ] Add multi-day weather forecasts
* [ ] Add temperature unit conversion (°C / °F)
* [ ] Add weather search autocomplete
* [ ] Improve error handling for invalid locations
* [ ] Add loading states and skeleton UI
* [ ] Add weather details such as humidity, wind speed, and pressure
* [ ] Improve mobile responsiveness
* [ ] Modernize the React dependencies
* [ ] Add automated tests
* [ ] Deploy the application publicly

## 📸 Preview

Add a screenshot or GIF of the application here:

```markdown
![Weather App Preview](./screenshot.png)
```

## 🤝 Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Commit your changes:

```bash
git commit -m "Add new feature"
```

5. Push the branch:

```bash
git push origin feature/your-feature
```

6. Open a Pull Request.

## 📄 License

This project is licensed under the **MIT License**. See the [`LICENSE`](./LICENSE) file for more information.

## 👨‍💻 Author

**Rishabh Shavare**

* GitHub: [@rishabh291202](https://github.com/rishabh291202)
* Project: [Weather App](https://github.com/rishabh291202/weather-app)

---

⭐ If you find this project useful, consider giving it a star!

