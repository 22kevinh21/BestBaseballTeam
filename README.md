# MLB Player and Pitcher Statistics Analysis

This project focuses on scraping and analyzing Major League Baseball (MLB) player and pitcher statistics. The goal is to extract relevant data, such as batting averages and earned run averages (ERAs), and perform various analyses on the collected data.

## Project Overview

The project is divided into two main parts:

1. **Player Data Analysis**
2. **Pitcher Data Analysis**

### Player Data Analysis

For the player data, we extract the highest batting averages for different positions (C, 1B, 2B, 3B, SS, LF, CF, RF, DH) and identify the top players overall. The data includes:
- Player name
- Batting average (AVG)
- Position

### Pitcher Data Analysis

For the pitcher data, we focus on extracting the lowest ERAs. The data includes:
- Pitcher name
- ERA (Earned Run Average)

## Data Extraction

The data is extracted from the MLB website using Selenium and BeautifulSoup. The extracted data is then saved into CSV files for further analysis.

### Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- selenium
- webdriver-manager
- beautifulsoup4

### Installation

To install the necessary dependencies, you can use the following command:
```bash
pip install pandas numpy matplotlib seaborn selenium webdriver-manager beautifulsoup4
