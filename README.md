![banner](http://d.gr-assets.com/misc/1454549184-1454549184_goodreads_misc.jpg)

<br>

![python_version](https://img.shields.io/badge/Python-v3.8-3776AB?style=for-the-badge&logo=Python)
![jupyter_version](https://img.shields.io/badge/Jupyter-v7.31.1-F37626?style=for-the-badge&logo=Jupyter)
![selenium_version](https://img.shields.io/badge/Selenium-v4.7.2-43B02A?style=for-the-badge&logo=Selenium)
![beautifulsoup_version](https://img.shields.io/badge/Beautifulsoup-v4-c2dfc3?style=for-the-badge&logo=Python)
![plotly_version](https://img.shields.io/badge/Plotly-v5.13.0-3F4F75?style=for-the-badge&logo=Plotly)
![MIT_License](https://img.shields.io/badge/License-MIT-9e1e32?style=for-the-badge&logo=)

<h1 align="center"> Arabic books analysis from goodreads </h1>
In this project I have tried to practice my data analysis skills by getting data from the internet clean it makes it ready for analysis then came up with some questions that may be useful in the business


## Contents
- [Website](https://www.ahmedel-kady.com/)
- Phase 1: Data Collection
- Phase 2: Data Cleaning
- Phase 3: Data Analysis and Visualization

## Website
Live Demo (from the books perspective): https://www.ahmedel-kady.com/books_project/books_perspective/

Live Demo (from the authors perspective): https://www.ahmedel-kady.com/books_project/books_perspective/


## 💾 Phase 1 Data Collection:
In this phase, I wanted to scrape Goodreads using Selenium and BeautifulSoup. However, I couldn't find a structure for the site or proper filters to extract the data, so I came up with the idea of using the ISBN, which is unique to each book, to obtain the book information. To do that, I needed to collect the ISBNs for Arabic books, so I decided to scrape both Neelwfrat and Diwan bookstores to gather all the ISBNs for the Arabic books. Once I collected the ISBNs, I was able to scrape the books from Goodreads using Selenium to automate the search for each ISBN and obtain the book information.


## 👨‍💻 Phase 2 Data Cleaning:
In this phase, I started with over 30,000 book titles. However, after the initial cleaning process, I ended up with 12,708 book titles that I had scraped from Goodreads. I removed duplicates and conducted further cleaning, which resulted in a final count of 10,500+ book titles that I used in my data analysis.


## 📊 Data Analysis and Visualization:
In this phase, I used Plotly to visualize a group of questions that I had selected to be answered with the data.

## 📝 License

This project is licensed under [MIT](https://opensource.org/licenses/MIT) license.

## 🧑‍🚀 Show your support

Give a ⭐️ if this project helped you!
