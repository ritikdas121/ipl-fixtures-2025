# IPL 2025 Match Schedule

## Overview
This project is a web application that displays the IPL 2025 match schedule. Users can view all matches or filter matches by selecting a specific team from a dropdown menu. The application is built using HTML, CSS, and JavaScript, with a responsive design that works on both desktop and mobile devices.

## Features
- **Match Display**: Shows a grid of match cards containing details like teams, date, venue, and winner.
- **Team Filter**: Allows users to filter matches by selecting a team from a dropdown menu.
- **Responsive Design**: Adapts to different screen sizes, ensuring a seamless experience on mobile and desktop.
- **Interactive UI**: Includes hover effects and animations for a polished user experience.

## File Structure
- `index.html`: The main HTML file that structures the webpage.
- `styles.css`: Contains all the CSS styling for the application, including a CSS reset, responsive design, and animations.
- `script.js`: JavaScript file that handles the match data and dynamic rendering of match cards based on user input.

## Setup Instructions
1. **Clone or Download**: Download the project files or clone the repository.
2. **Open the Project**:
   - Ensure all files (`index.html`, `styles.css`, `script.js`) are in the same directory.
   - Open `index.html` in a web browser to view the application.
3. **Dependencies**: No external dependencies are required. The project uses vanilla HTML, CSS, and JavaScript.

## Usage
- **View All Matches**: By default, the page displays all IPL 2025 matches.
- **Filter by Team**: Use the dropdown menu labeled "Filter by Team" to select a specific team. The grid will update to show only matches involving the selected team.
- **Responsive Experience**: Try resizing the browser window or accessing the page on a mobile device to see the responsive layout.

## Technologies Used
- **HTML5**: For structuring the webpage.
- **CSS3**: For styling, including CSS variables, grid layout, flexbox, and media queries.
- **JavaScript**: For dynamic content rendering and event handling.
- **Fonts**: Uses the Inter font family from Google Fonts.

## Notes
- The match data in `script.js` includes placeholders for future matches (e.g., "TBD" for teams or winners).
- The application assumes all match data is valid and correctly formatted in the `ipl2025Matches` array.
- The design uses a dark theme with a neon green accent color for visual appeal.

## Future Enhancements
- Add sorting options (e.g., by date or venue).
- Include match status indicators (e.g., live, upcoming, completed).
- Integrate an API to fetch real-time match data.

## License
This project is open-source and available under the MIT License.