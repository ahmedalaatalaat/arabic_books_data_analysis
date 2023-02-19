![banner](http://d.gr-assets.com/misc/1454549184-1454549184_goodreads_misc.jpg)

<br>

![python_version](https://img.shields.io/badge/Python-v3.8-3776AB?style=for-the-badge&logo=Python)
![jupyter_version](https://img.shields.io/badge/Jupyter-v7.31.1-F37626?style=for-the-badge&logo=Jupyter)
![selenium_version](https://img.shields.io/badge/Selenium-v4.7.2-43B02A?style=for-the-badge&logo=Selenium)
![beautifulsoup_version](https://img.shields.io/badge/Beautifulsoup-v4-c2dfc3?style=for-the-badge&logo=Python)
![plotly_version](https://img.shields.io/badge/Plotly-v5.13.0-3F4F75?style=for-the-badge&logo=Plotly)

# Arabic books analysis from goodreads
In this project I have tried to practice my data analysis skills by getting data from the internet clean it makes it ready for analysis then came up with some questions that may be useful in the business


## Contents
- [Live Demo](#website) 
- [Phase 1: Data Collection](#phase-1:-data-collection)
- Phase 2: Data Cleaning
- Phase 3: Data Analysis and Visulization

## Website
Live Demo: https://www.ahmedel-kady.com/jobs_project/jobs/


## 💾 Phase 1: Data Collection:
In this phase, I wanted to scrape Goodreads using Selenium and BeautifulSoup. However, I couldn't find a structure for the site or proper filters to extract the data, so I came up with the idea of using the ISBN, which is unique to each book, to obtain the book information. To do that, I needed to collect the ISBNs for Arabic books, so I decided to scrape both Neelwfrat and Diwan bookstores to gather all the ISBNs for the Arabic books. Once I collected the ISBNs, I was able to scrape the books from Goodreads using Selenium to automate the search for each ISBN and obtain the book information.
