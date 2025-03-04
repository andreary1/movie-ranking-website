# Movie Ranking Website

This is a simple web application inspired by "100 Days of Code: The Complete Python Pro Bootcamp" course, made by Angela Yu. It allows users to rank their top 10 favorite movies. The project is built using Python with Flask, SQLAlchemy, and WTForms. It also integrates Bootstrap for styling and The Movie Database (TMDB) API for fetching movie details.

## Features

- Add movies from TMDB to your ranking list.
- Search for a movie by title and select the correct one from a list of results.
- Rate movies from 0 to 10 and write a short review.
- Movies are stored in an SQLite database (`movies.db`).
- Edit the rating and review of a movie.
- Delete movies if they were added by mistake.

## Technologies Used

- **Flask** - Web framework for Python
- **SQLAlchemy** - Database ORM for managing SQLite
- **WTForms** - Form handling and validation
- **Bootstrap** - Frontend styling
- **TMDB API** - Fetching movie details

## Installation and Setup

1. Clone this repository:

   ```sh
   git clone https://github.com/your-username/movie-ranking-website.git
   cd movie-ranking-website
   ```

2. Install dependencies:

   ```sh
   pip install -r requirements.txt
   ```

3. Set up your TMDB API Key:

   - Log in to your [TMDB account](https://www.themoviedb.org/).
   - Go to account settings > API.
   - Follow the instructions to request an API key.
   - Replace `'your api key'` in `main.py` with your actual TMDB API key.

4. Run the application:

   ```sh
   python main.py
   ```

5. Open your browser and go to:

   ```
   http://127.0.0.1:5000/
   ```

## How It Works

1. Click **Add Movie** and enter a movie title.
2. Select the correct movie from the search results.
3. Provide a rating (0-10) and a short review.
4. The movie will be added to your list, ranked from least to most liked.
5. You can edit the rating and review or delete a movie from your list.

## Screenshots

- **Home Page** - Displays the ranked list of movies.
  
  ![screencapture-127-0-0-1-5000-2025-03-04-12_57_56](https://github.com/user-attachments/assets/419f917a-cde2-4004-b6cd-75d27bcee9fa)
  ![Captura de tela 2025-03-04 125943](https://github.com/user-attachments/assets/bbdc8bd4-291e-40cf-977c-83d8d830e03e)

- **Add Movie** - Allows users to search and select a movie.
  
  ![screencapture-127-0-0-1-5000-add-2025-03-04-13_00_33](https://github.com/user-attachments/assets/c9b0ced9-eb10-4a65-8e26-b9a30dc8b2b2)
  ![screencapture-127-0-0-1-5000-add-2025-03-04-13_00_56](https://github.com/user-attachments/assets/7a1114fb-9de9-4971-b40d-8dc8ee632671)
  
- **Edit Movie** - Lets users update the rating and review.

  ![screencapture-127-0-0-1-5000-edit-2025-03-04-12_58_54](https://github.com/user-attachments/assets/ebb3e16f-2153-4586-a9bb-1a686c5741b7)

## License

This project is licensed under the MIT License.
