# Problem Solving using Claude-3.5-Sonnet

## 📌 Overview

This Python script automates the process of solving LeetCode problems through web automation and the Claude AI API. It handles problem selection, generates solutions, and submits them automatically.

## 🚀 Key Features

- 🔹 **Automated login** to LeetCode  
- 🔹 **Problem navigation** through available challenges  
- 🔹 **Intelligent problem selection** based on difficulty and availability  
- 🔹 **AI-powered solution generation** using Claude AI  
- 🔹 **Automated code submission** with error handling  
- 🔹 **Retry mechanism** for improving failed solutions  

## 🛠️ Prerequisites

Ensure you have the following installed:

- Python 3.x  
- Selenium WebDriver  
- undetected_chromedriver  
- anthropic Python library  
- BeautifulSoup4  


## Usage

Run the script using Python:

1. CD to wherever you have the file stored.
2. Execute the script:
   ```
   python Solver.py
   ```

The script will automatically:
- Log in to LeetCode
- Navigate through problems
- Select a problem
- Generate a solution using Claude's 3.5 Sonnet API AI
- Submit the solution
- Handle any errors and retry if necessary
- Move on to the next problem

