# Animal Data Web Generator

A Python-based web tool that fetches real-time animal data from an external API and generates a stylish, structured HTML website based on user input.

## Features
- **Dynamic Search:** Users can search for any animal by name.
- **API Integration:** Fetches detailed information (diet, location, type, etc.) from the [API-Ninjas Animals API](https://api-ninjas.com/api/animals).
- **Template-Based Generation:** Uses an HTML template to create a clean, consistent user interface.
- **Error Handling:** Displays a user-friendly message if an animal is not found in the database.
- **Security:** Uses environment variables to protect sensitive API keys.

## Project Structure
- `animals_web_generator.py`: The main script that handles user input and HTML generation.
- `data_fetcher.py`: A specialized module for handling API requests.
- `animals_template.html`: The base template used for generating the website.
- `.env`: (Local only) Stores your private API_KEY.
- `requirements.txt`: Lists the necessary Python packages.

## Prerequisites
- Python 3.x
- An API Key from [API-Ninjas](https://api-ninjas.com/)

## Installation
To install this project, simply clone the repository and install the dependencies in requirements.txt using `pip`

## Usage
To use this project, run the following command - `python animals_web_generator.py`.

## Contributing Guidelines

Contributions make the open-source community an amazing place to learn and create!

1. **Fork the Project**
2. **Create your Feature Branch**
    ```bash
    git checkout -b feature/AmazingFeature

3. **Commit your Changes**
    ```bash
    git commit -m 'Add some AmazingFeature'
4. **Push to the Branch**
    ```bash
    git push origin feature/AmazingFeature
5. **Open a pull request**

Please ensure your code follows the existing modular structure and includes comments for new functions.