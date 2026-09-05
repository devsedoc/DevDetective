# DevDetective

DevDetective is a GitHub profile finder web application that allows users to search for GitHub users and view their profile information using the GitHub API.

## Features

* Search GitHub users by username
* Display GitHub profile information
* Show profile avatar
* Display user's name and GitHub username
* Show account creation date
* Display bio
* Show repository, follower, and following counts
* Display location
* Display personal website
* Display Twitter/X username
* Display company information
* Dark mode
* Responsive design

## Tech Stack

* HTML5
* CSS3
* JavaScript
* GitHub REST API
* Google Fonts

## Project Structure

```text
DevDetective/
│
├── assets/
│   ├── images/
│   │   ├── company-icon.svg
│   │   ├── location-icon.svg
│   │   ├── moon-icon.svg
│   │   ├── search-icon.svg
│   │   ├── sun-icon.svg
│   │   ├── twitter-icon.svg
│   │   └── website-icon.svg
│   │
│   ├── android-chrome-192x192.png
│   ├── android-chrome-512x512.png
│   ├── apple-touch-icon.png
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon.ico
│   └── site.webmanifest
│
├── index.html
├── styles.css
├── script.js
└── README.md
```

## How It Works

1. Enter a GitHub username in the search bar.
2. Click the **Search** button.
3. The application sends a request to the GitHub API.
4. The user's profile data is retrieved.
5. The profile information is displayed on the page.

## GitHub API

This project uses the GitHub REST API to retrieve user profile information.

API endpoint:

```text
https://api.github.com/users/{username}
```

Example:

```text
https://api.github.com/users/octocat
```

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/devsedoc/DevDetective.git
```

### Navigate to the Project

```bash
cd DevDetective
```

### Run the Project

Open `index.html` directly in your browser.

For development, you can use the **Live Server** extension in Visual Studio Code.

## Usage

Enter any valid GitHub username in the search bar.

Example:

```text
octocat
```

The application will fetch the user's GitHub profile and display the available information.

If the username does not exist, an error message will be displayed.

## Future Improvements

* Display GitHub repositories
* Add repository search and filtering
* Display GitHub activity
* Add loading animation
* Improve accessibility
* Add GitHub API authentication for higher API rate limits

## Author

**Devang Sharma**

GitHub: https://github.com/devsedoc

## License

This project is created for learning and educational purposes.
