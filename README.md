# Web Scraper

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project contains a web scraper that retrieves news articles and data from a website.

![](https://github.com/Prakashpsk/Web-Scraper/blob/main/Presentation1.png)


## What I Am Doing in This Project
In this project, I first import libraries such as pandas, requests, BeautifulSoup, etc. Then, I scrape data from Amazon and convert it to a CSV file. I also handle null values in the scraped data.

## Features
- Retrieve news articles using the News API.
- Scrape data from a website using Selenium and BeautifulSoup.
- Organize and store data in a structured format.
- Print and display data for analysis.

## Installation
1. Clone the repository to your local machine:
    ```
    git clone https://github.com/your-username/your-repo-name.git
    ```
2. Install the required dependencies using pip:
    ```
    pip install -r requirements.txt
    ```
3. Download and place the ChromeDriver executable in the project directory or update the `webdriver.Chrome()` path in the code to the appropriate location.

## Usage
1. Run the `main.py` script.
2. Follow the prompts to enter the keyword for news articles and the location for web scraping.
3. The script will fetch news articles, display JSON output, and create a DataFrame for news articles. It will also perform web scraping, display the scraped data, and save it to a CSV file.

## Technologies Used
- Python
- Requests
- Selenium
- BeautifulSoup
- Pandas

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request.

## About the Author
P. Prakash is a Data Scientist with expertise in web scraping, data analysis, and machine learning. You can contact him at prakash2822001@gmail.com.

