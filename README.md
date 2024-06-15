# web_scraping
# Event Data Scraper

## Overview
This Python script scrapes event information from Eventbrite and saves it into a CSV file. It extracts details such as Event Name, Event Date(s), Location, Website URL, Description, Key Speakers, Agenda/Schedule, Registration Details, Pricing, Categories, and Audience type.

## Requirements
- Python 3.x
- `requests` library
- `beautifulsoup4` library
- `csv` library

## Installation
1. Clone the repository to your local machine.
   ```sh
   git clone https://github.com/yourusername/event-data-scraper.git
   cd event-data-scraper

# Install the required Python libraries.
pip install requests beautifulsoup4

# Usage
1. Edit the scraper.py script to include the URLs of the events we want to scrape.
2. Run the script.
3. The script will scrape the event data and save it to a CSV file named events_data.csv in the project directory.

# Summary of the Data Collected
The script extracts detailed information from event pages, including:

Event Name: Name of the event.
Event Date(s): Date and time of the event.
Location: Venue where the event is held.
Website URL: URL of the event page.
Description: Description of the event, including its purpose and highlights.
Key Speakers: Notable speakers or participants.
Agenda/Schedule: Timetable or agenda of the event activities.
Registration Details: How to register or attend the event.
Pricing: Cost associated with attending the event.
Categories: Tags or categories related to the event.
Audience type: Target audience for the event.
