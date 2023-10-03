# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# Movie search application

# API to use:
- https://www.omdbapi.com/
- API_KEY: 4287ad07

# Requirements:

- It needs an input to write de movie and a button to search it.
- List the finded movies and show the title, year and poster.
- The movies has to be displayed in a responsive grid.

# First iteration:
- Avoid doing the same search twice in a row.
- Do that the search has doing automatically at type.
- Avoid doing the search continuously at type (debounce).