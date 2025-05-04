![VA Logo](assets/va_logo.png)

# Automated VA Website Scraper

![Python](https://img.shields.io/badge/Python-3.9%2B-blue) ![Selenium](https://img.shields.io/badge/Selenium-WebDriver-4.0%2B-brightgreen) [ChromeDriver](https://img.shields.io/badge/ChromeDriver-Headless--compatible-blue) 

*Structured, headless data extraction from the U.S. Department of Veteran Affairs site*

---

## 🚀 Project Overview

> This **Python** scraper navigates the **VA website** — handling dynamic pagination, JavaScript-driven content, and anti-bot protections — all in **headless** mode (no visible browser). Built for **reliability**, **performance**, and **extensibility**.

---

## ✨ Key Features


- 🕶️ **Headless Chrome**  
  Runs ChromeDriver in headless mode to eliminate UI overhead and integrate seamlessly on servers or pipelines.

- 🔄 **Automated Pagination**  
  Auto-detects “Next” controls or page numbers and iterates through all pages—no manual page-count configuration.

- 🔧 **Dynamic Content Handling**  
  Combines implicit & explicit waits with robust CSS/XPath selectors for asynchronous elements (e.g., JS-rendered tables).

- 🛡️ **Error Handling & Retries**  
  Built-in retry logic for timeouts, stale-element exceptions, and transient network issues ensures uninterrupted runs.

- 🧩 **Modular Codebase**  
  - **`BaseScraper`**: WebDriver setup/teardown, logging utilities  
  - **Handler Classes**: Page-specific navigation & parsing logic  
  - **Utilities**: Wait helpers, retry decorators in `utils.py`

- 📦 **Flexible Output**  
  Switch between **CSV** and **JSON** with a single line change in the export method.
