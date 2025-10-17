# Captcha Solver Web App

This is a simple, single-file web application designed to help users input and submit solutions for CAPTCHA images. It provides a user-friendly interface to either upload a CAPTCHA image from your local machine or load one directly from a URL. While this frontend application does not perform actual OCR (Optical Character Recognition) or backend validation, it serves as a robust foundation for integrating such functionalities.

## Features

*   **Image Upload**: Easily upload CAPTCHA images from your computer.
*   **URL Image Support**: Load CAPTCHA images directly from a given URL.
*   **Responsive Design**: The application adapts gracefully to various screen sizes, from mobile devices to desktops, thanks to Tailwind CSS.
*   **User Input**: A dedicated field for users to type their perceived CAPTCHA solution.
*   **Submission Feedback**: Provides basic feedback upon submission of the solution.
*   **Single-File Deployment**: All HTML, CSS (Tailwind via CDN), and JavaScript are contained within a single `index.html` file for easy deployment.

## Getting Started

To get this application up and running, simply follow these steps:

1.  **Clone the repository** (or copy the `index.html` file to your local machine):
    ```bash
    git clone https://github.com/your-username/captcha-solver-app.git
    cd captcha-solver-app
    ```
    *Note: If you don't have `sample.png`, the app will display a placeholder image initially. You can either place your own `sample.png` in the root or use the URL input feature.* 

2.  **Open `index.html`**: Double-click the `index.html` file in your browser, or open it via a local web server.

    That's it! The application should load in your browser, ready for use.

## Usage

1.  **Load Captcha Image**:
    *   Click the "Upload Captcha Image" button to select an image file from your computer.
    *   Alternatively, paste an image URL into the "Or paste image URL here" input field and click "Load from URL".
2.  **Enter Solution**: Once the CAPTCHA image is displayed, type the characters you see into the "Your Captcha Solution:" input field.
3.  **Submit**: Click the "Submit Solution" button. The application will acknowledge your submission.

## Technologies Used

*   **HTML5**: For the core structure of the web page.
*   **Tailwind CSS**: A utility-first CSS framework for highly responsive and customizable styling.
*   **JavaScript**: For interactive elements, image loading logic, and basic form handling.

## Future Enhancements (Planned)

*   Integration with a backend for actual CAPTCHA generation and validation.
*   Implementation of OCR (Optical Character Recognition) on the backend for automated solving attempts.
*   Advanced UI/UX improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
