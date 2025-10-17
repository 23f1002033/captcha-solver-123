# Captcha Solver Frontend

A simple, responsive single-page HTML application designed to display a captcha image and allow users to input their solution. Built with Tailwind CSS for modern styling.

## Features

- **Dynamic Captcha Loading**: Loads captcha images either from a default local file (`sample.png`) or from a specified URL via a query parameter.
- **Responsive Design**: Adapts seamlessly to various screen sizes using Tailwind CSS.
- **User Input**: Provides an input field for users to enter the captcha text.
- **Client-Side Simulation**: Simulates captcha submission and provides feedback (note: actual verification requires a backend).

## Getting Started

To run this application, simply open the `index.html` file in your web browser.

## Usage

### Default Captcha

When opened without any URL parameters, the app will display `sample.png`:

```
file:///path/to/your/project/index.html
```

### Loading Captcha from a URL

You can specify a captcha image URL using the `?url=` query parameter in the browser's address bar. For example:

```
file:///path/to/your/project/index.html?url=https://example.com/some/image.png
```

Replace `https://example.com/some/image.png` with the actual URL of your captcha image.

## Technology Stack

- HTML5
- Tailwind CSS (CDN)
- JavaScript

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.