# Tennis Rankings Tracker

## Overview

The Tennis Rankings Tracker is a Python-based application designed to scrape and visualize the performance of tennis players over time. It gathers data from TennisExplorer.com and presents it in an easy-to-use graphical interface.

## Features

- **Track Weekly Rankings**: The application fetches weekly rankings for ATP and WTA players.
- **YTD Change Calculation**: Calculates the Year-to-Date (YTD) change in points for each player.
- **Expand/Collapse Weekly Points**: Allows users to expand or collapse the weekly point details for each player.
- **Color-Coded Performance**: Players' performances are color-coded from green (positive) to red (negative) based on YTD change.
- **Last Updated**: Displays the last update date based on the latest available data.

## Installation

### Prerequisites

- Python 3.7+
- `pip` package manager

### Setup

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-username/tennis-rankings-tracker.git
   cd tennis-rankings-tracker

## Installation

### Install Required Python Packages:

```sh
pip install -r requirements.txt


### 1. **Install ChromeDriver**

```markdown
### Install ChromeDriver:

#### Download ChromeDriver:
- Go to the [ChromeDriver download page](https://sites.google.com/a/chromium.org/chromedriver/downloads) and download the version that matches your installed version of Chrome.

#### Extract the Executable:
- Extract the downloaded file to a directory on your computer.

#### Add ChromeDriver to System Path:

- **Windows**:
  - Add the directory containing `chromedriver.exe` to your system's PATH.
  - Steps:
    1. Right-click on `This PC` or `Computer`, and select `Properties`.
    2. Click `Advanced system settings`.
    3. In the `System Properties` window, click the `Environment Variables` button.
    4. In the `System variables` section, find the `Path` variable, and click `Edit`.
    5. Add the path to the directory containing `chromedriver.exe` and click `OK`.

- **Mac/Linux**:
  - You can add the path to `chromedriver` to your system PATH by adding the following line to your `~/.bash_profile` or `~/.bashrc` file:
    ```sh
    export PATH=$PATH:/path/to/chromedriver
    ```
  - Then, reload your profile:
    ```sh
    source ~/.bash_profile
    ```

## Run the Application

To run the application, use the following command:

```sh
python tennisranking.py



### 3. **Usage**

```markdown
## Usage

- Upon running the script, the application will open a graphical user interface.
- Users can track tennis players' rankings, visualize their weekly performance, and monitor their year-to-date changes.


## Building the Executable

To build the executable using PyInstaller, run the following command:

```sh
pyinstaller --onefile --windowed tennisranking.py



### 5. **Acknowledgments**

```markdown
## Acknowledgments

- Data sourced from [TennisExplorer.com](https://www.tennisexplorer.com).

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
