# Forkify Recipe Search Application

Forkify is a web application that allows users to search for recipes, view recipe details, and manage bookmarks. Users can search over 1,000,000 recipes, view recipe details, and add their favorite recipes to bookmarks. The app also provides functionalities to add new recipes.

## Features

- **Search Recipes**: Search for recipes by ingredients or recipe names.
- **View Recipe Details**: View detailed information about a selected recipe.
- **Manage Bookmarks**: Save favorite recipes to bookmarks for easy access.
- **Add New Recipes**: Upload and add new recipes to the application.

## Technologies Used

- **HTML5**: Structure and layout of the web application.
- **CSS/Sass**: Styling of the application.
- **JavaScript**: Dynamic functionalities and interactions.
- **Webpack**: Module bundler to manage JavaScript modules.
- **OpenWeather API**: Fetches recipe data (you'll need to replace with appropriate recipe API).

## Setup and Installation

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Dependencies**:

   Make sure you have Node.js and npm installed. Install the project dependencies by running:

   ```bash
   npm install
   ```

3. **Build the Project**:

   Build the project files with Webpack:

   ```bash
   npm run build
   ```

4. **Run the Project**:

   Start a local server to view the project:

   ```bash
   npm start
   ```

   Visit `http://localhost:8080` in your browser.

## Usage

1. **Search for Recipes**:

   - Enter a recipe or ingredient in the search field and click "Search."

2. **View Recipe Details**:

   - Click on a recipe from the search results to view its details.

3. **Add to Bookmarks**:

   - Click the bookmark icon on a recipe to add it to your bookmarks.

4. **Add New Recipe**:
   - Click on "Add recipe" in the navigation menu to upload a new recipe.

## File Structure

- `index.html`: Main HTML file with structure and content.
- `src/sass/main.scss`: Main stylesheet for the application.
- `src/js/controller.js`: JavaScript file managing application logic and event handling.
- `src/js/model.js`: JavaScript file managing data and state.
- `src/js/views/`: Directory containing view files for rendering different parts of the application.

## Contributing

Feel free to fork the repository and submit pull requests. For any issues or feature requests, please open an issue on the repository.

## License

This project is open-source and available under the [MIT License](LICENSE). You are free to use, modify, and distribute the code according to the terms of the license.

## Contact

For any questions or feedback, please refer to the contact details provided in the repository.

---

Enjoy exploring and managing recipes with Forkify!
