# Driver Work Frequency Monitor

This application was developed with the assistance of ChatGPT to monitor the work frequency of drivers. Its primary objective is to track and count the number of working days for each driver within a given month.

The application employs a Selenium WebDriver to authenticate and scrape data from a designated website, identifying which drivers are actively working. Subsequently, it aggregates the total number of drivers present on each day to determine the cumulative working days per driver. This information is then communicated via Telegram in the form of a summary message, providing an overview of the drivers' attendance.

The application is configured to reset its data monthly, thereby commencing a new count at the beginning of each month. This functionality enables ongoing monitoring and comparison of drivers’ work frequencies over time.

---

## Features

- Automated login and data scraping using Selenium
- Tracking and counting of drivers’ working days
- Monthly reset of collected data
- Telegram notifications summarizing driver attendance

---

## Technologies Used

- Python
- Selenium
- Telegram API

---
