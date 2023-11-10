# creepjs-Project# Web Scraping and Data Processing using Selenium

## Overview

This project focuses on automating web scraping and data processing tasks using Selenium with Chrome to gather information from the [creepjs](https://abrahamjuliot.github.io/creepjs/) website. The objective is to stealthily scrape data related to trust score, lies, bot detection, and fingerprint/FP ID. The solution employs creative web scraping techniques, including randomizing user-agent strings and emulating human-like behavior.

## Steps

1. **GitHub Repository:**
   - A GitHub repository has been created to house the code, scripts, and generated data.

2. **Selenium Web Scraping:**
   - Utilizing Selenium, the script navigates to the creepjs website and extracts information for the specified fields.

3. **Data Extraction:**
   - The script pulls information for:
     - Trust Score
     - Lies
     - Bot detection
     - Fingerprint/FP ID

4. **Data Storage:**
   - Extracted data is saved in JSON format (`scraped_data.json`) for each run.

5. **PDF Generation:**
   - The script captures the entire webpage and saves it as a PDF (`page_1.pdf`).

6. **Repeated Execution:**
   - The entire process is repeated three times, generating a total of 6 files.

7. **Priority on Trust Score:**
   - The script prioritizes achieving the highest trust score during execution.

## Notes and Challenges

- **User Agents:**
  - A pool of 500 user agents is randomly generated to emulate diverse browser environments.

- **Headless Mode:**
  - The script operates in headless mode to mimic human-like behavior.

- **Challenges:**
  - Challenges faced during implementation are detailed in the code comments.

## Repository Contents

- `scrape_script.py`: The main Python script for web scraping using Selenium.
- `scraped_data.json`: JSON file containing the extracted data.
- `page_1.pdf`: PDF capturing the entire webpage during the first run.
- Additional files (`page_2.pdf`, `scraped_data_2.json`, `page_3.pdf`, `scraped_data_3.json`) generated during subsequent runs.

Feel free to explore the code, scripts, and generated data. The repository provides a comprehensive view of the web scraping process and its outcomes.
