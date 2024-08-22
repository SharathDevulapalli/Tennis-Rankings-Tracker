# Tennis Rankings Tracker

The Tennis Rankings Tracker is a Python application designed to scrape and visualize the performance of ATP and WTA tennis players over time. It collects data from TennisExplorer.com and presents it in a graphical user interface (GUI) for easy analysis of weekly rankings and year-to-date (YTD) point changes.

## Features

- **Track Weekly Rankings:** Automatically fetches weekly rankings for ATP and WTA players.
- **YTD Change Calculation:** Calculates the Year-to-Date (YTD) change in points for each player based on the first and most recent available data.
- **Expandable Player Data:** Users can expand/collapse player rows to view weekly point details.
- **Color-Coded Performance:** Players' performances are color-coded from green (positive) to red (negative) based on their YTD change.
- **Data Sources:** Pulls live ranking data from TennisExplorer.com.
- **Last Updated Date:** Displays the last update date based on the most recent available data.

## Installation

### Prerequisites

- Python 3.7+
- pip package manager
- Chrome web browser
- ChromeDriver

### Setup

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/tennis-rankings-tracker.git
   cd tennis-rankings-tracker
