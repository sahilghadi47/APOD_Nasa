# NASA React App

This project is a simple React application that fetches data from the NASA Astronomy Picture of the Day (APOD) API and displays it. The app includes a main content area, a sidebar, and a footer.

## Components

**App.jsx**
This is the main component that handles fetching data from the NASA API and manages the state of the application.

**Footer.jsx**
Displays the footer of the app. It also contains a button to toggle the sidebar.

**Main.jsx**
Displays the main content of the app, which includes the NASA Astronomy Picture of the Day.

**SideBar.jsx**
Displays additional information about the Astronomy Picture of the Day in a sidebar.

## API Integration

The application fetches data from the NASA APOD API. It uses the NASA API key stored in the environment variable VITE_NASA_API_KEY.

The fetched data is cached in localStorage for the current day to avoid unnecessary API requests.
