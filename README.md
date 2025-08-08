# Minimalist Startpage

A clean and minimalist new tab page that displays a personalized greeting and a dynamic, real-time age counter.

## Features

-   **Personalized Greeting:** Displays a "Welcome" message with a customizable name.
-   **Real-Time Age Counter:** Shows your age, updating every second.
-   **Customizable Theme:** Choose between a light theme, a dark theme, or a dynamic theme that changes with the sunrise and sunset.

## Usage

To use this startpage, you need a browser extension that can override the new tab page with a local HTML file. 

I recommend using [Custom New Tab](https://chromewebstore.google.com/detail/custom-new-tab/lfjnnkckddkopjfgmbcpdiolnmfobflj) for Chrome.

Once you have the extension installed, point it to the `index.html` file in this repository.

## Customization

To personalize the start page, simply edit the `config.js` file.

### Basic Configuration

-   `name`: Set this to your name.
-   `birthDate`: Set this to your birthdate to get an accurate age counter.

### Advanced Configuration

-   `theme`: Choose your preferred theme.
    -   `'light'`: Always use the light theme.
    -   `'dark'`: Always use the dark theme.
    -   `'dynamic'`: (Default) Automatically switch between light and dark themes based on sunrise and sunset.
-   `sunriseHour` and `sunsetHour`: If you use the `dynamic` theme, you can adjust these values to better match your local time or preference.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
