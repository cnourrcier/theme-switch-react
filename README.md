# Light and Dark Theme Switch

This project is a simple React application that allows users to toggle between light and dark themes. It uses a custom hook, useLocalStorage, to persist the theme selection in the browser's local storage, ensuring the selected theme is maintained even after the user refreshes the page or closes and reopens the browser. The project consists of the following components:

## Custom Hook: useLocalStorage

- Purpose: To manage state with local storage.
- Functionality:
    - Initializes the state with a value from local storage or a default value if none exists.
    - Updates the local storage whenever the state changes.

## Component: LightDarkMode

- Purpose: To provide a user interface for toggling between light and dark themes.
- Functionality:
    - Uses the useLocalStorage hook to store and retrieve the theme.
    - Contains a button that toggles the theme between light and dark.
    - Applies the selected theme to the component's CSS class.