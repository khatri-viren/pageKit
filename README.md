# pageKit

Streamline form data management with our Flask-powered toolkit, allowing you to effortlessly capture and organize user submissions in a local Excel file.

## Features

- **Simple Integration**: Easily incorporate form handling capabilities into your Flask web application.
- **Local Excel Storage**: Seamlessly store form submissions in a local Excel file for convenient data management.
- **User-Friendly**: Designed with simplicity in mind, making it accessible for developers of all levels.

## Quick Start

1. Clone the repository:

   ```bash
   git clone https://github.com/khatri-viren/pageKit.git
   ```

2. Navigate to the project directory:

   ```bash
    cd pageKit
   ```

3. Install dependencies:

   ```bash
    pip install -r requirements.txt
   ```

4. Run the application:

   ```bash
   gunicorn wsgi:app
   ```

   Open the link provided in the terminal window to view the application. Should look something like this:

   ```bash
     Listening at: http://127.0.0.1:8000
   ```

## Configuration

Adjust the configuration as needed in config.py, and consider using environment variables for sensitive information.

## Contributing

Contributions are welcome! Feel free to open issues and submit pull requests.
