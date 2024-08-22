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

2. **Install Required Packages:**
   ```sh
   pip install -r requirements.txt

3. **Install ChromeDriver:**

   - **Download ChromeDriver:**
     Go to the [ChromeDriver download page](https://sites.google.com/a/chromium.org/chromedriver/downloads) and download the version that matches your installed version of Chrome.

   - **Extract the Executable:**
     Extract the downloaded file to a directory on your computer.

   - **Add ChromeDriver to System Path:**

     - **Windows:**
       1. Right-click on `This PC` or `Computer`, and select `Properties`.
       2. Click `Advanced system settings`.
       3. In the System Properties window, click the `Environment Variables` button.
       4. In the System variables section, find the `Path` variable, and click `Edit`.
       5. Add the path to the directory containing `chromedriver.exe` and click `OK`.

     - **Mac/Linux:**
       Add the path to `chromedriver` to your system `PATH` by adding the following line to your `~/.bash_profile` or `~/.bashrc` file:
       ```sh
       export PATH=$PATH:/path/to/chromedriver
       ```
       Then reload your profile:
       ```sh
       source ~/.bash_profile
       ```
4. **Run the Application:**

To run the application, use the following command:
   ```sh
   python tennisranking.py

Once the application is running, a GUI will open. Users can:
   1. View and track player rankings week-by-week.
   2. Expand player rows to see their weekly point changes.
   3. Monitor YTD point changes for each player.

### Usage 

Upon running the script, the GUI will present player rankings, visualizing both ATP and WTA data in separate tabs. You can expand each player to see weekly points and collapse it back when needed. The last updated date is shown at the top of the interface, based on the latest data fetched.

### Build the Executable 

To build the executable using PyInstaller, use the following command:
   '''sh
   pyinstaller --onefile --windowed tennisranking.py

The executable will be found in the _'dist'_ directory

### Contributing

If you want to contribute to this project:
      Fork the repository.
      Create a new feature branch.
      Make your changes and ensure they are tested.
      Create a pull request to the main repository.

### Acknowledgments

   1. Data sourced from TennisExplorer.com.
   2. Special thanks to contributors for their help and inspiration.
