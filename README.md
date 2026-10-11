# Arena — Gaming Tournament Portal

Arena is a simple web-based tournament management portal for gaming competitions. It provides a dashboard to view tournaments, teams, matches, leaderboard standings, and recent activity.

## Features

- **Demo login** with Organizer, Player, and Spectator roles
- **Dashboard** showing tournament counts, live tournaments, registered teams, and prize pools
- **Tournament management** to create tournaments with a game, format, mode, date, team limit, and prize pool
- **Team registration** with team names, tags, and player lists
- **Match scheduling** between registered teams
- **Match results** that organizers can update and publish
- **Leaderboard** calculated from posted match results
- **Live activity feed** for registrations, tournament updates, and results
- **Responsive layout** for desktop and smaller screens
- **Browser local storage** to keep demo data on the same browser

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Browser Local Storage
- Google Fonts (Space Grotesk and Inter)

## Getting Started

### Requirements

- A web browser such as Chrome, Edge, or Firefox
- Optional: Visual Studio Code for editing the project

### Run the project

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Open `project1.html` in your browser.

   **Optional:** Install the **Live Server** extension in VS Code, right-click `project1.html`, and select **Open with Live Server**.

## Demo Login

This is a front-end demo. Enter any username and a password with at least 4 characters, then choose a role:

- **Organizer** — create tournaments, schedule matches, and post results
- **Player** — view tournament information and register teams
- **Spectator** — follow tournaments, matches, and standings

The login is for demonstration only. It does not provide real user authentication or account security.

## How It Works

1. The user signs in using the demo login screen.
2. The dashboard displays tournament and team statistics.
3. Organizers can create tournaments and schedule matches.
4. Teams can be registered with player names.
5. Organizers can enter scores and post match results.
6. The leaderboard calculates points from completed matches: 3 points for a win and 1 point for each team in a draw.
7. Tournament data is saved in the browser's Local Storage.

## Project Structure

```text
GAMING-TOURNMNET-PORTAL/
├── project1.html
└── README.md
```

## Important Notes

- This project currently uses front-end JavaScript and browser Local Storage; it does not include a server-side database.
- Data is stored in the browser on the device where the project is used. It is not automatically shared between users or devices.
- The login is a demo and should not be used to protect real accounts or sensitive information.
- Some tournament and team information is sample data included to demonstrate the portal.

## Future Improvements

- Add a backend API and database.
- Implement secure authentication and role-based permissions on the server.
- Add real-time match updates.
- Add tournament brackets and automated match progression.
- Add player profiles, team invitations, and notifications.
- Deploy the portal online.

## Author

**Lakshman Thota**

## License

This project is provided for educational and demonstration purposes. Add a license file if you want to specify permissions for reuse.
