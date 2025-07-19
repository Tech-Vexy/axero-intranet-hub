# Axero Intranet Hub

A modern, responsive intranet portal designed to enhance workplace collaboration and productivity.

![Axero Intranet Hub Screenshot](screenshot.png)

## Features

- **User Authentication** with role-based access control
- **Interactive Dashboard** with real-time metrics and announcements
- **Team Spotlights** for employee recognition
- **Calendar System** with event management
- **Employee Directory** with contact information
- **Device Management System** for tracking company equipment
- **Communication Hub** with chat functionality
- **Weather Widget** with real-time data and geolocation
- **Activity Feed** showing recent activities
- **Dark/Light Mode** toggle
- **Keyboard Shortcuts** for productivity
- **Search Functionality** with clickable results
- **Admin Panel** for system management

## Technologies Used

- HTML5
- CSS3 (with CSS variables and Grid layout)
- Vanilla JavaScript
- IndexedDB for client-side data persistence
- OpenWeatherMap API for real-time weather data
- Geolocation API for location-based services

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/axero-intranet-hub.git
   ```

2. Open `index.html` in your browser.

3. Login with one of the following credentials:
   - Username: `admin`, Password: `admin123` (Administrator access)
   - Username: `user`, Password: `user123` (Regular user access)
   - Username: `alex`, Password: `alex123` (Regular user access)

## Usage

### Keyboard Shortcuts

- `Ctrl/Cmd + K`: Open global search
- `Ctrl/Cmd + D`: Toggle dark/light mode
- `Ctrl/Cmd + M`: Open message composer
- `Ctrl/Cmd + C`: Open calendar
- `Ctrl/Cmd + E`: Open device management
- `Ctrl/Cmd + N`: Add new event (when calendar is open) or device
- `Escape`: Close any open modal

## Data Persistence

The application uses IndexedDB to store:
- Calendar events
- Device information
- Chat messages
- Activity records
- User preferences

User authentication data is stored in either localStorage (for "Remember Me" option) or sessionStorage (for session-only login), providing secure access control while maintaining user preferences.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Created for the [Frontend Challenge: Office Edition sponsored by Axero](https://dev.to/challenges/frontend/axero)
- Weather icons from [OpenWeatherMap](https://openweathermap.org/)
- Sample profile images from [RandomUser.me](https://randomuser.me/)