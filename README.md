# Steam Game Price Tracker

This project is a web scraping tool designed to track the price of a desired game on Steam. When the price drops below a specified threshold, the tool sends an email notification to the user, alerting them to the price change.

## Features

- Scrapes the price, reviews, ratings, and system requirements of a specified game on Steam.
- Tracks the price over time and records the data in a CSV file.
- Sends an email alert to the user when the game's price falls below a certain threshold.

## Installation

To install and run this project, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
2. **Install the required libraries:**

Ensure you have Python installed, then install the necessary packages:

  ```bash
  pip install beautifulsoup4 requests pandas
  ```

3. **Usage**
   Set up email credentials:

   Replace 'achal3450singh@gmail.com' and 'xxxxxxxxxxxxxxx' in the send_mail function with your email address and app password, respectively.

    Run the script:

    Execute the script to start tracking the game's price:

  ```bash
      python price_tracker.py
  ```
