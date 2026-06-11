# Skyglass — Weather App 🌤️

A beautiful, responsive real-time weather application built with vanilla HTML, CSS, and JavaScript. Get instant weather data, forecasts, and atmospheric intelligence for any city in the world.

## ✨ Features

### Current Weather Display
- 🌍 **City & Country Information** - See weather for any location globally
- 🌡️ **Real-time Temperature** - Current temperature with "feels like" index
- ☁️ **Weather Conditions** - Detailed weather descriptions with emoji indicators
- 📊 **Temperature Range** - High and low temperatures for the day

### Quick Stats
- 💧 **Humidity** - Relative humidity percentage
- 🌬️ **Wind Speed & Direction** - Wind speed with cardinal direction (N, NE, E, etc.)
- 🌡️ **Atmospheric Pressure** - Pressure in hectopascals (hPa)
- 👁️ **Visibility** - Visibility range in kilometers

### Sun & UV Information
- 🌅 **Sunrise & Sunset Times** - Exact times with day length calculation
- ☀️ **UV Index** - UV radiation level (Low, Moderate, High, Very High, Extreme)
- ☁️ **Cloud Cover** - Cloud coverage percentage

### Forecasts
- ⏰ **Hourly Forecast** - Next 8 hours weather prediction
- 📅 **5-Day Outlook** - Extended forecast with temperature ranges and humidity

### Additional Features
- 💨 **Air Quality Index (AQI)** - Air quality status (Good, Fair, Moderate, Poor, Very Poor)
- 🔄 **Temperature Units** - Toggle between Celsius (°C) and Fahrenheit (°F)
- 🔍 **City Search** - Search weather for any city worldwide
- 📍 **Location Detection** - Use your device's geolocation for instant weather
- 🎨 **Beautiful UI** - Modern glassmorphism design with smooth animations
- 📱 **Responsive Design** - Fully responsive on desktop, tablet, and mobile

## 🎨 Design Highlights

- **Glassmorphism UI** - Frosted glass effect with backdrop blur
- **Animated Background** - Twinkling stars and aurora effects
- **Smooth Animations** - Transitions and visual feedback on interactions
- **Color Scheme** - Deep sky blues, cyan accents, and golden sunlight
- **Typography** - Multiple elegant font families (DM Serif Display, Inter, JetBrains Mono)

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for weather API calls)

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/8168575/assignment-1-Bootcamp-weather-.git
cd assignment-1-Bootcamp-weather-
```

2. **Open the application:**
   - Double-click `index.html` to open in your default browser
   - Or right-click and select "Open with" your preferred browser
   - Or use a local server (optional for better performance)

### Using with a Local Server (Optional)

For better performance, serve the file over HTTP:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (http-server)
npx http-server

# Using Live Server in VS Code
# Install "Live Server" extension and right-click → Open with Live Server
```

Then open: `http://localhost:8000`

## 🌐 API Integration

This application uses the **OpenWeatherMap API** for real-time weather data.

- **Current Weather API** - Live weather conditions
- **Forecast API** - 5-day weather forecast with hourly data
- **Free Tier** - Supports up to 60 API calls per minute

**API Key:** Pre-configured (included in the application)

## 📖 Usage Guide

### Search for a City
1. Enter a city name in the search box (e.g., "London", "Tokyo", "Mumbai")
2. Press Enter or click the "Search" button
3. Weather data will load instantly

### Use Your Location
1. Click the "Use my location" button
2. Allow browser permissions for geolocation
3. Weather for your current location will display

### Toggle Temperature Units
- Click **°C** for Celsius (metric)
- Click **°F** for Fahrenheit (imperial)
- All temperatures will update automatically

### Explore Weather Details
- **Scroll down** to see hourly forecast and 5-day outlook
- **Hover over forecast rows** for interactive effects
- **Check air quality indicators** for pollution status

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with:
  - CSS Grid and Flexbox
  - CSS Variables (custom properties)
  - Backdrop filters and animations
  - Media queries for responsiveness
- **JavaScript (ES6+)** - Application logic with:
  - Fetch API for HTTP requests
  - Promise.all for parallel API calls
  - Arrow functions and template literals
  - DOM manipulation and event handling

### External Services
- **Google Fonts** - DM Serif Display, Inter, JetBrains Mono
- **OpenWeatherMap API** - Real-time weather data

## 📁 Project Structure

```
weather/
├── index.html          # Main application file
└── README.md           # This file
```

**Single-file architecture:** The entire application (HTML, CSS, and JavaScript) is contained in `index.html` for easy deployment and sharing.

## 🎯 Key Features Explained

### Weather Emoji System
Different weather conditions display appropriate emojis:
- ☀️ Clear sky
- ⛅ Few clouds
- ☁️ Overcast
- 🌧️ Rain
- ⛈️ Thunderstorm
- 🌨️ Snow
- 🌙 Night clear sky

### Temperature Calculation
- High/Low from hourly forecast data
- "Feels like" calculated with wind chill
- Accurate conversion between Celsius and Fahrenheit

### UV Index Levels
- **0-2**: Low (green)
- **3-5**: Moderate (yellow)
- **6-7**: High (orange)
- **8-10**: Very High (red)
- **11+**: Extreme (dark red)

### Air Quality Index
- **1**: Good (Green)
- **2**: Fair (Lime)
- **3**: Moderate (Yellow)
- **4**: Poor (Orange)
- **5**: Very Poor (Red)

## 🌍 Supported Locations

Works with any city that OpenWeatherMap recognizes:
- Capital cities
- Major metropolitan areas
- Towns and villages
- Multiple cities with same name (searchable by country)

Examples:
- London, UK
- New York, USA
- Tokyo, Japan
- Mumbai, India
- Sydney, Australia
- Paris, France

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Safari  | ✅ Full |
| Edge    | ✅ Full |
| Opera   | ✅ Full |
| IE 11   | ❌ Not supported |

## ♿ Accessibility Features

- Semantic HTML structure
- High contrast color scheme
- Respects `prefers-reduced-motion` setting
- Keyboard navigation support
- Clear visual hierarchy

## 🐛 Known Limitations

1. **Air Quality Index (AQI)** - Estimated from humidity data (would require separate API call for actual AQI)
2. **UV Index** - Calculated from cloud cover (proxy calculation)
3. **Forecast Data** - Limited to available forecast days from API
4. **Offline Mode** - Requires internet connection for weather data

## 🔮 Future Enhancements

- [ ] Multiple city comparison
- [ ] Weather alerts and notifications
- [ ] Favorite cities bookmark system
- [ ] Detailed weather charts and graphs
- [ ] Weather radar integration
- [ ] Air pollution map
- [ ] Pollen forecast
- [ ] Local storage for search history
- [ ] Dark/Light theme toggle
- [ ] Multilingual support

## 📄 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

### Suggested Improvements:
- Better error handling
- Loading state animations
- Weather alert system
- Accessibility enhancements
- Performance optimizations
- Additional weather metrics

## 📧 Support

For issues or questions:
- Check the [GitHub Issues](https://github.com/8168575/assignment-1-Bootcamp-weather-/issues)
- Review OpenWeatherMap API documentation
- Check browser console for error messages

## 🙏 Credits

- **Weather Data**: [OpenWeatherMap API](https://openweathermap.org/api)
- **Fonts**: [Google Fonts](https://fonts.google.com)
- **Design Inspiration**: Modern glassmorphism UI trends
- **Icons**: Unicode emoji characters

## 📝 Bootcamp Assignment Info

- **Assignment**: Bootcamp Assignment 1
- **Project**: Weather Web Application
- **Completion Date**: June 11, 2026
- **Author**: 8168575
- **Repository**: [GitHub - assignment-1-Bootcamp-weather-](https://github.com/8168575/assignment-1-Bootcamp-weather-)

---

**Made with ❤️ for real-time weather intelligence**

Enjoy exploring weather around the world! 🌍🌤️
