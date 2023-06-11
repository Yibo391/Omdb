# OMDB Project

This project is a TV show search application built using React and Redux. It uses the OMDB API to retrieve TV show information and episode data.

## Features

- Enter a TV show name in the search box and click the search button to search for the show's episodes.
- Display the title, episode list, and average rating of the TV show.
- Click on an episode in the list to view detailed information about that episode.
- Supports asynchronous loading and display of episode data.

## Tech Stack

- React: JavaScript library for building user interfaces.
- Redux: State management library for managing the application state and data flow.
- Axios: Library for making HTTP requests.
- Bootstrap: CSS framework for building responsive layouts.

## Installation and Usage

1. Clone the project to your local machine:
git clone https://github.com/your-username/omdb-project.git


2. Navigate to the project directory:
cd omdb-project


3. Install dependencies:
npm install


4. Start the development server:
npm start


5. Access the application in your browser:
http://localhost:3000


## Configuration

In the `src/api/index.js` file, you need to modify the `API_BASE_URL` to your own OMDB API address.

## Sample Data

The example data in the application is fetched by calling the OMDB API. You can add more API methods in the `src/api` directory or modify them based on your needs.

## Contributing

Contributions to this project are welcome! If you find any issues or have any improvement suggestions, please submit an Issue or Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).


