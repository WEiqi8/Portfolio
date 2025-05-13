# AsiaTime - Interactive Clock & Weather Dashboard for Asian Cities

## Project Overview

AsiaTime is an elegant web application that combines a classic analog clock with real-time weather information for 20 major Asian cities. This dashboard provides users with accurate time representation through both analog and digital displays, alongside current weather conditions and forecasts for selected metropolitan areas across Asia.

## Features

- **Dual Clock Display**:
  - Realistic analog clock with hour, minute, and second hands
  - Digital 24-hour time format with seconds precision
  
- **Comprehensive Weather Dashboard**:
  - Current temperature and weather conditions
  - Daily temperature range (high/low)
  - 5-hour forecast with temperature trends
  - 5-day weather outlook with temperature ranges
  
- **City Selection**:
  - Interactive buttons for 20 major Asian cities
  - Instantly switch between different city weather data
  - Visual indication of currently selected city

- **Visual Weather Indicators**:
  - Material design icons representing different weather conditions
  - Color-coded temperature display
  - Clean, responsive layout

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: Bootstrap 5
- **Icons**: Google Material Symbols
- **API**: OpenWeatherMap API for real-time weather data
- **Asynchronous Handling**: Modern async/await pattern

## Implementation Details

The application leverages several technical features:

- **Dynamic Time Calculation**: Real-time calculation of hand positions for precise analog clock representation
- **API Integration**: Fetches and processes weather data from OpenWeatherMap
- **Data Processing**: Implements algorithms to determine the most common weather conditions for each day
- **Responsive Design**: Adapts seamlessly to different screen sizes
- **Dynamic DOM Manipulation**: Creates and updates UI elements based on fetched data

## Getting Started

1. Clone the repository
2. Replace the `apiKey` variable in script.js with your OpenWeatherMap API key
3. Open index.html in your browser or deploy to your preferred hosting service

## City Coverage

AsiaTime provides weather information for the following cities:
- Tokyo, Singapore, Beijing, Mumbai, Seoul
- Bangkok, Kuala Lumpur, Manila, Hanoi, Jakarta
- Taipei, Delhi, Astana, Karachi, Dhaka
- Kathmandu, Ulaanbaatar, Yangon, Phnom Penh, Vientiane

## Future Enhancements

- User location detection for automatic city selection
- Unit toggle between Celsius and Fahrenheit
- Dark/light theme options
- Weather alerts and notifications
- Historical weather data visualization

## Screenshots
![image](https://github.com/user-attachments/assets/a40acff7-4297-42cf-9c94-460f795a787c)
![image](https://github.com/user-attachments/assets/f507a0bf-ce11-4073-bf8e-326a4e62df16)
![image](https://github.com/user-attachments/assets/3c7cf442-af40-42d5-ace7-219a3f5700c9)


## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Designed with ❤️ for travelers, expatriates, and anyone interested in Asian weather patterns.