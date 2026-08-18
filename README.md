# GitHub Analytics Dashboard

A full-stack analytics application that helps developers understand GitHub repository activity through interactive metrics and visualizations.

The application retrieves repository data through the GitHub API and analyzes contributor activity, commits, issues, pull requests, and development trends.

## Demo

A demo video of the application is included in this repository:

https://github.com/madhumithabharadwaj/spm/assets/49988224/dec94249-c21b-4210-921c-444851331f10

## Features

* Analyze GitHub repository activity and development trends
* Track contributor activity and commit frequency
* Analyze issue activity and resolution patterns
* Examine pull request activity
* Retrieve repository information using the GitHub API
* Visualize repository metrics through an interactive frontend
* Support GitHub authentication for accessing repository data

## Tech Stack

**Frontend**

* React.js
* JavaScript
* Material UI
* Bootstrap
* Axios

**Backend**

* Python
* Flask
* GitHub REST API

**Tools & APIs**

* GitHub API
* Octokit
* Git
* GitHub

## How It Works

1. The user provides or authenticates access to GitHub repository data.
2. The application retrieves repository information through the GitHub API.
3. The Flask backend processes repository activity and development metrics.
4. The React frontend presents the resulting analytics through an interactive interface.

## Repository Structure

```text
github-analytics-dashboard/
├── Login_Page/     # Authentication-related components
├── public/         # Static frontend assets
├── src/            # React frontend and Flask/backend logic
├── package.json    # Frontend dependencies and scripts
└── README.md
```

## Running the Project

Install the frontend dependencies:

```bash
npm install
```

Start the React development server:

```bash
npm start
```

The application will run locally at:

```text
http://localhost:3000
```

## Project Purpose

This project was developed to provide a consolidated view of GitHub repository activity and make it easier to identify development patterns, contributor activity, and potential workflow bottlenecks from repository data.

## Future Improvements

* Move API credentials to environment variables
* Improve authentication and credential management
* Add additional repository health metrics
* Expand automated testing
* Improve deployment configuration
