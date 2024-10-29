# 🎬 Hybrid Recommendation Systems

A **movie recommendation system** built with **JavaScript** and **React**, utilizing **The Movie Database (TMDb) API** to provide personalized movie recommendations. The project structure is organized to ensure scalability, modularity, and ease of maintenance.

---

## 📖 Overview

This project combines multiple recommendation techniques, including collaborative and content-based filtering, to offer personalized movie suggestions. The app fetches real-time movie data from **TMDb API** and provides users with a responsive, clean, and visually appealing interface.

---

## 🚀 Features

- **TMDb API Integration**: Fetches movie data for real-time recommendations.
- **Hybrid Recommendation Algorithms**: Blends collaborative and content-based filtering.
- **Modular Components**: Organized folder structure for easy maintenance.
- **Responsive UI**: Simple, intuitive design with reusable components.

---

## 🛠 Tech Stack

- **JavaScript**: Core language for application logic.
- **React**: Front-end library for building user interfaces.
- **CSS**: Styling components for a responsive and clean UI.
- **HTML**: Structure for rendering content.
- **TMDb API**: Provides movie data for recommendations.

---

## 📂 Project Structure

Here’s a breakdown of the project structure:

```
Hybrid-Recommendation-Systems/
├── public/                       # Public assets accessible to the client
│   ├── favicon.ico               # Favicon for the project
│   ├── index.html                # Main HTML file
│   ├── logo192.png               # Logo for web app (192x192)
│   ├── logo512.png               # Logo for web app (512x512)
│   ├── logoOur.png               # Custom logo for the project
│   ├── manifest.json             # Web app manifest for PWA support
│   ├── ourlogo.svg               # SVG logo
│   ├── robots.txt                # Instructions for web crawlers
│   └── trace.svg                 # Additional SVG graphic
│
├── src/                          # Source files for the application
│   ├── components/               # Reusable UI components
│   │   ├── card/                 # Movie card component
│   │   │   ├── card.css          # Styles for the card component
│   │   │   └── card.js           # Logic for rendering each movie card
│   │   ├── header/               # Header component for navigation
│   │   │   ├── Header.css        # Styles for the header
│   │   │   └── Header.js         # Header component logic
│   │   └── movieList/            # Movie list component to display movies
│   │       ├── movieList.css     # Styles for the movie list
│   │       └── movieList.js      # Logic for displaying the movie list
│
│   ├── pages/                    # Main pages for the application
│   │   ├── home/                 # Home page of the application
│   │   │   ├── home.css          # Styles for the home page
│   │   │   └── home.js           # Home page component logic
│   │   └── movieDetail/          # Detailed page for individual movies
│   │       ├── movie.css         # Styles for the movie detail page
│   │       └── movie.js          # Logic for displaying movie details
│
│   ├── App.css                   # Global app styling
│   ├── App.js                    # Main app component combining all components and pages
│   ├── index.css                 # Global CSS settings
│   └── index.js                  # Entry point of the app
│
├── .gitignore                    # Specifies files and folders to ignore in Git
├── package-lock.json             # Lockfile for npm dependencies
├── package.json                  # Project metadata and dependencies
└── README.md                     # Project documentation
```

---

## ⚙️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AbhishekS04/Hybrid-Recommendation-Systems.git
   cd Hybrid-Recommendation-Systems
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Add TMDb API Key**  
   Sign up on [TMDb](https://www.themoviedb.org/) to get your API key and add it in the relevant configuration file (`config.js` or directly in the code).

4. **Run the Application**
   ```bash
   npm start
   ```

---

## 📝 Usage

- **Home Page**: The main page displays a list of recommended movies.
- **Movie Details Page**: Click on any movie to view detailed information, including ratings, genre, and a brief description, all fetched from the TMDb API.
- **Search Functionality**: Allows users to search for movies by title.

---

## 🤝 Contributing

1. **Fork the repository**.
2. **Create a new branch** (`git checkout -b feature-branch`).
3. **Commit your changes** (`git commit -m 'Add new feature'`).
4. **Push to the branch** (`git push origin feature-branch`).
5. **Create a Pull Request**.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

For questions or feedback, reach out via:
- **GitHub Issues**: [Report Issues](https://github.com/AbhishekS04/Hybrid-Recommendation-Systems/issues)
- **LinkedIn**: [Connect with Abhishek](https://www.linkedin.com/in/abhishek-singh-045312292/)
