# Popcorn-Portal 

Popcorn-Portal is a modern movie discovery web application built with React. It allows users to search for their favorite movies and explore different categories using the OMDb API.

## Features

-   **Movie Search**: Real-time search functionality to find movies by title.
-   **Movie Details**: View movie posters and basic information.
-   **Categories**: Browse movies by genres like Action, Drama, and Comedy.
-   **Responsive Design**: Optimized for both desktop and mobile devices.

## Tech Stack

-   **Frontend**: React.js
-   **Routing**: React Router
-   **API**: OMDb API
-   **Styling**: CSS

## Getting Started

### Prerequisites

-   Node.js installed on your machine.
-   An API key from [OMDb API](http://www.omdbapi.com/apikey.aspx).

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd popcorn-portal
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  Create a `.env` file in the root directory and add your OMDb API key:
    ```env
    REACT_APP_OMDB_API_KEY=your_api_key_here
    ```
5.  Start the development server:
    ```bash
    npm start
    ```

The application will open in your browser at `http://localhost:3000`.
