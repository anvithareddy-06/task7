# User Data Fetch App

This project fetches and displays a list of users from a public API (`https://jsonplaceholder.typicode.com/users`) using JavaScript. It is designed to demonstrate data fetching, error handling, DOM manipulation, and basic styling.

## Features

- Fetches user data (name, email, address) from the JSONPlaceholder API
- Displays each user's information in styled cards
- Handles network/API errors gracefully
- Reload button to re-fetch user data
- Responsive and clean layout using CSS

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- [JSONPlaceholder](https://jsonplaceholder.typicode.com/) as the mock REST API

## How It Works

1. On page load, a fetch request is made to retrieve user data.
2. The response is parsed from JSON and displayed in the browser.
3. Each user’s name, email, and address are shown in a styled card.
4. If an error occurs (like internet disconnection), a message is shown.
5. A "Reload Data" button lets users manually re-fetch the data.

## Example User Output

Name: Leanne Graham
Email: Sincere@april.biz
Address: Kulas Light, Gwenborough, 92998-3874

 This is just sample data. The app shows 10 users by default.

## Notes

- Data is from a **mock API** and cannot be modified or saved permanently.
- POST/PUT/DELETE operations are **simulated only** on JSONPlaceholder.
- 
## Testing Instructions

- Open 'ndex.html'
-  in a browser with internet access
- Disable your internet and click "Reload Data" to test error handling
- Observe user cards and error messages


