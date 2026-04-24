# My-Zootopia-API

An educational web generator that displays information about animals from the Animals API.

## Tech Stack

- **Backend**: Python
- **Frontend**: HTML
- **API**: Animals API (api-ninjas.com)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/84edu/My-Zootopia-API.git
cd My-Zootopia-API
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your API key:
   - Get a free API key from [api-ninjas.com](https://api-ninjas.com/)
   - Create a `.env` file in the project root:
   ```
   API_KEY=your_api_key_here
   ```

## Usage

Run the web generator:
```bash
python animals_web_generator.py
```

Enter an animal name when prompted. The script will:
1. Fetch animal data from the Animals API
2. Generate an HTML page with the animal information
3. Save it as `animals.html`

## Project Structure

- `animals_web_generator.py` - Main script to generate HTML pages
- `data_fetcher.py` - Fetches animal data from the API
- `animals_template.html` - HTML template for displaying animals
- `animals_data.json` - Sample animal data
- `animals.html` - Generated output file

## License

Educational purposes only.
