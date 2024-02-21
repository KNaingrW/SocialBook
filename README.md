Dark Mode Toggle

This is a simple web application that allows users to toggle between light and dark modes. It consists of an HTML file, a CSS file, and a JavaScript file.
Features

    Dark Mode Toggle: Users can switch between light and dark modes by clicking on a button.
    Persistent Theme: The selected theme (light or dark) is stored in the browser's local storage, so it persists across sessions.

Files

    index.html: This file contains the structure of the web page. It includes a button for toggling dark mode and a placeholder for the main content.
    styles.css: This file contains the styles for the web page, including the dark mode styles. It defines the color scheme and other visual elements for both light and dark modes.
    script.js: This file contains the JavaScript code for toggling the dark mode and handling the local storage. It listens for clicks on the dark mode toggle button and updates the page's appearance accordingly. It also stores the current theme in the browser's local storage.

Usage

To use this application, simply open the index.html file in a web browser. Click on the dark mode toggle button to switch between light and dark modes. The selected theme will persist across sessions due to local storage.
How It Works

    When the page loads, the JavaScript code checks the local storage for the current theme (light or dark).
    If a theme is found in local storage, it applies that theme to the page by adding the appropriate classes to the button and the body element.
    If no theme is found in local storage (for example, on the first visit), it defaults to the light theme and stores it in local storage for future visits.
    When the dark mode toggle button is clicked, the JavaScript code toggles the dark-btn-on class on the button and the dark-theme class on the body element to switch between light and dark modes.
    It also updates the theme stored in local storage accordingly, so the selected theme persists across sessions.

Customization

You can customize the appearance of the light and dark modes by modifying the styles in the styles.css file. Adjust colors, fonts, and other visual elements to suit your preferences or match your website's design.
Credits

This project was created by [Kyaw Naing Win]. Feel free to reach out with any questions or feedback!
