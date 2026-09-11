# 🕷️ CodeAlpha Task 1 — Web Scraping

## 📌 Project Overview

This project demonstrates **web scraping using Python** to extract useful and structured information from a public website.

For this task, **Books to Scrape** was used as the data source. The website is designed specifically for practicing web scraping and provides a collection of books with information such as title, price, rating, and availability.

The scraped information is converted into a structured dataset using **Pandas** and saved as a CSV file for further analysis.

---

## 🎯 Objectives

* Learn the fundamentals of web scraping.
* Understand the structure of HTML web pages.
* Extract relevant information using **BeautifulSoup**.
* Handle multiple pages using pagination.
* Create a custom dataset from publicly available web data.
* Clean and organize the extracted data.
* Perform basic data analysis and visualization.
* Save the scraped information in CSV format.

---

## 🛠️ Technologies Used

| Technology          | Purpose                              |
| ------------------- | ------------------------------------ |
| 🐍 Python           | Programming language                 |
| 🌐 Requests         | Download webpage HTML                |
| 🔎 BeautifulSoup    | Parse and extract HTML data          |
| 🐼 Pandas           | Data processing and dataset creation |
| 📊 Matplotlib       | Data visualization                   |
| 📈 Seaborn          | Statistical visualization            |
| 📓 Jupyter Notebook | Development and documentation        |

---

## 🌐 Data Source

**Website:** Books to Scrape

The website provides fictional book information for web-scraping practice.

The scraper collects information from multiple pages instead of extracting data from only a single webpage.

---

## 📊 Data Collected

The following fields are extracted:

* **Title** — Name of the book
* **Price_GBP** — Book price in GBP
* **Rating** — Rating converted from words to numbers
* **Availability** — Stock availability
* **Product_URL** — Link to the individual book page

### Example

| Title                |  Price | Rating | Availability |
| -------------------- | -----: | -----: | ------------ |
| A Light in the Attic | £51.77 |      3 | In stock     |
| Tipping the Velvet   | £53.74 |      1 | In stock     |
| Soumission           | £50.10 |      1 | In stock     |

---

## 🔄 Web Scraping Workflow

```text
Public Website
      ↓
Send HTTP Request
      ↓
Receive HTML
      ↓
Parse HTML using BeautifulSoup
      ↓
Identify Book Elements
      ↓
Extract Book Information
      ↓
Handle Pagination
      ↓
Create Pandas DataFrame
      ↓
Clean Dataset
      ↓
Export CSV
      ↓
Data Analysis & Visualization
```

---

## 📂 Project Structure

```text
CodeAlpha_Task1_Web_Scraping/
│
├── Task_1_Web_Scraping.ipynb
├── scraper.py
├── README.md
├── requirements.txt
│
└── data/
    └── books_dataset_sample.csv
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/CodeAlpha_Task1_Web_Scraping.git
```

### 2. Navigate to the project

```bash
cd CodeAlpha_Task1_Web_Scraping
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the scraper

```bash
python scraper.py
```

The scraper will collect book information from the website and create:

```text
data/books_dataset.csv
```

### 5. Open the Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
Task_1_Web_Scraping.ipynb
```

Run the cells to view the scraping process, dataset, analysis, and visualizations.

---

## 📈 Data Analysis

After collecting the data, basic analysis is performed to understand:

* Average book price
* Minimum and maximum prices
* Distribution of book ratings
* Most expensive books
* Relationship between price and rating
* Availability information

Visualizations include:

* 📊 Rating distribution
* 📚 Top 10 most expensive books
* 📦 Price distribution by rating

---

## 🧹 Data Cleaning

The scraped data is cleaned before analysis by:

* Converting prices into numeric values.
* Converting rating words into numerical values.
* Checking for missing values.
* Checking and removing duplicate records.
* Organizing the data into a structured Pandas DataFrame.

---

## 💡 Key Learning Outcomes

Through this project, I learned:

1. How websites are structured using HTML.
2. How to send HTTP requests using Python.
3. How to parse HTML using BeautifulSoup.
4. How to locate elements using CSS selectors.
5. How to extract data from repeated HTML elements.
6. How to handle website pagination.
7. How to create custom datasets.
8. How to clean scraped data using Pandas.
9. How to visualize collected data.
10. How web scraping can support data analysis projects.

---

## ⚖️ Ethical Web Scraping

This project uses **Books to Scrape**, a website created specifically for web-scraping practice.

The scraper also includes a small delay between requests to avoid sending unnecessary rapid requests to the website.

Web scraping should always respect a website's terms, robots.txt, access restrictions, and applicable laws.

---

## 🔮 Future Improvements

Possible improvements include:

* Scraping additional book categories.
* Collecting more detailed product information.
* Adding automated data cleaning.
* Creating an interactive dashboard using Power BI.
* Performing exploratory data analysis.
* Automating periodic dataset updates.
* Applying price and rating analysis to identify trends.

---

## 👩‍💻 Author

**Nisha Nayak**

BCA Student | Aspiring Data Analyst & Web Developer

---

## 🏆 Internship

**CodeAlpha Internship — Task 1**

### Task: Web Scraping

This project was developed to demonstrate practical knowledge of Python-based web scraping, data extraction, dataset creation, and basic data analysis.

---

## ⭐ Acknowledgement

Thanks to **Books to Scrape** for providing a dedicated practice environment for learning web scraping.
