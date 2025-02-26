# Github-Scraper

## 📌 Overview
Github-Scraper is a Python-based tool that scrapes the GitHub topics page to extract top repositories within popular topics. It collects repository names, stats (such as stars, forks, etc.), and contributors. The data is saved in a neatly formatted CSV file for easy analysis.

## 🚀 Features
- Extracts repository names, stats, and contributors from GitHub topics.
- Outputs the collected data in a neatly formatted CSV file.
- Utilizes popular Python libraries such as BeautifulSoup, Selenium, Pandas, and Requests.

## 🛠️ Installation
### Prerequisites
- macOS (Tested on Mac)
- Python 3.13 installed
- Jupyter Notebook installed

### Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/shauryasaxenas/Github-Scraper.git
   cd Github-Scraper
   ```
2. Create and activate a virtual environment:
   ```bash
   python3 -m venv WebScraping
   ```
3. Install dependencies:
   ```bash
   pip install requests --upgrade --quiet
   pip install beautifulsoup4 --upgrade --quiet
   pip install pandas --upgrade --quiet
   pip install selenium --upgrade --quiet
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open the latest .ipynb notebook version (e.g. github_scraper_v3.ipynb) and run the cells sequentially.

## 📂 Usage
Run the scraper by executing the Jupyter Notebook cells. The script will scrape the top repositories from GitHub topics and save the data into CSV files.

## 📊 Output
- Each GitHub topic will have its own CSV file.
- All CSV files will be stored in a folder named **data**
- Each CSV file will contain the following columns:
   - Repository Name
   - Stars
   - Forks
   - Number of Contributors

## 📦 Dependencies 
- **Requests** for making HTTP requests
- **BeautifulSoup** for parsing HTML
- **Pandas** for data manipulation
- **Selenium** for dynamic page interactions

## 💬 Contact
For any issues or questions, feel free to open an issue on the repository.
