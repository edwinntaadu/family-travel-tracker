# Travel Tracker

## Description
Travel Tracker is a web application designed to help users track the countries they have visited. Users can add countries, switch between user profiles, and visualize their travel progress on a map.

## Features
- **User Profiles:** Create and switch between profiles with custom colors.
- **Track Countries:** Add countries to a personal visited list.
- **Dynamic Map:** Highlight visited countries on a world map.

## Technologies Used
- **Backend:** Node.js, Express
- **Database:** PostgreSQL
- **Frontend:** HTML, CSS, JavaScript (EJS templates)
- **Styling:** CSS with custom stylesheets

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd travel-tracker
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Up Database:**
   - Create a PostgreSQL database named `world`.
   - Add the required tables:
     - `users`: To store user profiles.
     - `visited_countries`: To store visited countries for each user.
     - `countries`: To store a list of all countries and their codes.
   - Update database credentials in the code as necessary.

4. **Run the Server:**
   ```bash
   npm start
   ```
   The application will run on `http://localhost:3000`.

5. **Access the Application:**
   - Navigate to `http://localhost:3000` in your browser.

## Usage
- On the homepage, select a user or add a new user.
- Use the input box to add a country by name.
- Visited countries will be highlighted on the map.

## Future Enhancements
- Add user authentication.
- Integrate API for real-time country data.
- Enhance map interactivity.


