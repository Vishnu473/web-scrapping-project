# Web Scraping Project

This project is a web scraping application that extracts information about places to visit in India from the website [Holidify](https://www.holidify.com/country/india/places-to-visit.html). The data is stored in a structured JSON format for further analysis or usage.

## Table of Contents
- [Usage](#usage)
- [Features](#features)
- [Running Locally](#running-locally)
- [Running in Google Colab](#running-in-google-colab)
- [Saving Data](#saving-data)
- [License](#license)
- [Contributing](#contributing)

## Usage
To run this project, you can execute the notebook in Google Colab or locally on your machine. The scraped data will be saved in a JSON file named `places_data.json`.

## Features
- **Scraping Multiple Pages:** Fetch data from multiple pages of the Holidify website using pagination.
- **Extracting Key Information:** Extract the name of the place, image URLs, tourist attraction count, and best time to visit.
- **Handling JSON Data:** Store the scraped data in a structured JSON file (places_data.json).
- **Customizable:** The code can be modified to scrape additional properties or target different websites.

### Running Locally
1. Make sure you have Python installed on your system.
2. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/repository-name.git
    ```
3. Navigate to the project directory:
    ```bash
    cd repository-name
    ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
5. Run the notebook:
    ```bash
    jupyter notebook WebScrappingProject.ipynb
    ```

### Running in Google Colab
1. Open [notebook](https://colab.research.google.com/github/Vishnu473/web-scrapping-project/blob/main/WebScrappingProject.ipynb) in Google Colab.
2. Run the cells in the notebook to execute the web scraping script.

## Saving Data
The scraped data is stored in a JSON file with the following structure:

```json
[
    {
        "name": "Place Name",
        "image": ["image_url1", "image_url2"],
        "rating": "Rating",
        "link": "Link to detailed page",
        "info": "Information about the place",
        "time": ["Best time to visit"],
        "tourist_attractions_count": "Count of tourist attractions"
    },
    ...
]




