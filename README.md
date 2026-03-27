# Recipe Book

A modern, responsive recipe book application built with React and TypeScript. This application allows users to view, search, and manage their favorite recipes.

## Features

- **Recipe List**: Browse all recipes with filtering capabilities.
- **Recipe Details**: View detailed information about each recipe, including ingredients and instructions.
- **Search**: Quickly find recipes by name.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (or yarn)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd recipe-book
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

Start the development server:

```bash
npm start
```

The application will open in your browser at `http://localhost:3000`.

## Project Structure

```
src/
├── components/      # Reusable React components
│   ├── RecipeCard.tsx
│   ├── RecipeList.tsx
│   └── SearchBar.tsx
├── data/            # Mock recipe data
│   └── recipes.ts
├── pages/           # Page components
│   ├── HomePage.tsx
│   └── RecipePage.tsx
├── App.tsx          # Main application component
├── index.tsx        # Entry point
└── styles.css       # Global styles
```

## Technologies Used

- **React**: UI library for building the user interface.
- **TypeScript**: Static type checking for JavaScript.
- **CSS**: Styling and layout.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with ❤️ using React and TypeScript**
