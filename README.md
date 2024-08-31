React Hacker News Search App
This is a simple React application that allows users to search for articles from Hacker News using the Algolia search API. The application includes a search bar, a paginated list of results, and handles loading and error states gracefully.

Features
Search Bar: Allows users to input a query and search for related articles on Hacker News.
Pagination: Displays search results in a paginated format, allowing users to navigate through pages of results.
Loading and Error Handling: Provides visual feedback for loading and handles any errors that may occur during data fetching.
Project Structure
App(): The main component that contains the search bar, manages the state, and displays search results.
Pagination(): A component that handles pagination for the list of search results.
useDataApi(): A custom hook for managing API calls, loading states, and error handling.
dataFetchReducer(): A reducer function for handling different states of data fetching (init, success, failure).
Getting Started
Follow these instructions to run the app locally.

Prerequisites
Node.js and npm installed on your local machine.

Installation
Clone the Repository:
Navigate to the Project Directory:
Install Dependencies:


Start the Development Server:
Open your browser and go to http://localhost:3000 to see the app in action.

Usage
Search for Articles: Use the search bar to type in a keyword and press the "Search" button.
Pagination: Use the pagination buttons to navigate through different pages of search results.


License
This project is open-source and available under the MIT License.


