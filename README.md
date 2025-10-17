# CAPTCHA Solver App

This is a simple, single-file web application designed to display a CAPTCHA image and allow users to input their solution. It's built with HTML and styled using Tailwind CSS, providing a responsive and user-friendly interface.

## Features

*   **Responsive Design:** Adapts to various screen sizes, from mobile to desktop.
*   **Tailwind CSS:** Modern utility-first CSS framework for clean and maintainable styling.
*   **Dynamic Image Loading:** Can load CAPTCHA images from a URL specified in the query parameters or default to a local sample image.
*   **Basic Client-Side Validation:** Provides a basic simulated validation for the default sample CAPTCHA.
*   **Single-File Application:** All HTML, CSS (via CDN), and JavaScript are contained within a single `index.html` file, making it easy to deploy and share.

## Usage

To use this application:

1.  **Open `index.html`** in your web browser.
2.  The application will display a default CAPTCHA image (`sample.png`) by default.
3.  **To load a custom CAPTCHA image**, append a `?url=` query parameter to the URL in your browser's address bar.
    *   **Example:** `file:///path/to/your/index.html?url=https://example.com/some-captcha-image.png`
    *   The application will attempt to load the image from the provided URL.
4.  **Enter the CAPTCHA text** into the input field and click "Submit".
    *   For the default `sample.png` image, the expected answer is `ADUR3`.

## Local Development

Simply open the `index.html` file directly in your web browser. No special server setup is required.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.