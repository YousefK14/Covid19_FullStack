# Coronavirus (COVID-19) Full Stack Application

## Overview
The idea behind this application is to display the statistics of Coronavirus COVID-19 around the world. The data is collected from [Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE)](https://github.com/CSSEGISandData/COVID-19) and is constantly updated to reflect the latest cases worldwide.

## Technical Overview
This is a full-stack application built using:

- **Front-end:** React.js
- **Back-end:** Node.js
- **Database:** MongoDB (to store parsed data)

Additionally, it uses **Mapbox** to visualize coordinates on the map in the GeoJSON format.

## Features
- Displays global COVID-19 statistics including total cases, recoveries, and deaths.
- Provides country-specific statistics with real-time updates.
- Interactive map populated using Mapbox to highlight affected regions.
- User-friendly interface for searching specific country data.

## How It Works
1. The application fetches data from [JHU CSSE](https://github.com/CSSEGISandData/COVID-19) in real time.
2. The data is stored and managed in a MongoDB database.
3. The front-end uses React.js to dynamically display statistics and map data.
4. Mapbox is used to render an interactive map, visualizing COVID-19 spread globally using GeoJSON data.

## Installation and Setup
### Prerequisites
- Node.js installed
- MongoDB setup
- Mapbox API key

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/covid-tracker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd covid-tracker
   ```
3. Install dependencies for both front-end and back-end:
   ```bash
   npm install
   ```
4. Configure environment variables:
   - Set up a `.env` file with the following:
     ```env
     MAPBOX_API_KEY=your_mapbox_api_key
     MONGODB_URI=your_mongodb_connection_string
     ```
5. Start the application:
   ```bash
   npm run dev
   ```

## API Usage
The application uses APIs to:
- Fetch COVID-19 statistics from JHU CSSE.
- Populate the database with parsed data.
- Serve the front-end with country-specific and global statistics.

## Technologies Used
- **React.js**: For building the user interface.
- **Node.js**: For handling the back-end logic.
- **MongoDB**: For storing COVID-19 data.
- **Mapbox**: For rendering the interactive map.

## Contribution
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push to your fork.
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

