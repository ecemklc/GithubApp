# GitHub User Profile App

This application allows users to search for GitHub profiles and view detailed information about them, including their repositories. It provides a user-friendly interface to explore GitHub profiles and their public repositories.

## Features

- Search for GitHub users
- Display user profile information
- View a list of repositories for the user
- Handle loading states and errors gracefully

## Technologies Used

- React
- GitHub API
- Styled Components
- Fetch API for HTTP requests

## Installation

1. Clone the repository
2. Change to the project directory:

    ```bash
    cd github-user-profile-app
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory and add your GitHub token:

    ```
    VITE_GITHUB_TOKEN=your_github_token
    ```

5. Run the application:

    ```bash
    npm run dev
    ```

## Project Structure

src
├── components
│ ├── Form.jsx
│ ├── ListItem.jsx
│ ├── Profile.jsx
│ ├── RepoCard.jsx
│ ├── Repos.jsx
│ └── Spinner.jsx
├── request.js
├── App.jsx
├── App.css
└── index.js


## Components

### Form.jsx
Handles user input and form submission for searching GitHub profiles.

### ListItem.jsx
Displays individual list items with optional icons.

### Profile.jsx
Displays detailed user profile information.

### RepoCard.jsx
Displays individual repository information.

### Repos.jsx
Displays a list of repositories using RepoCard components.


## API Requests

### request.js
Handles API requests to GitHub.

## Usage
1. Open the app in your browser.
2. Enter a GitHub username in the search input and click "Search" to fetch the user's profile and repositories.
3. View the profile details and repositories of the searched user.