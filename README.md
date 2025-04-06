# Reddit Comment Engagement Analysis

**Course:** DATA 410  
**Lead Author:** Aarav Gosalia  
**Contributors:** Aarav Gosalia, Aleric Govender, Jordi Capdevila Maso

---

## Project Overview

This repository contains a data science project analyzing factors that drive higher engagement on Reddit comments. The project was conducted for a DATA 410 class and involves data collection, exploratory data analysis, and multiple regression models to predict comment popularity. The analysis emphasizes the role of metadata over sentiment in determining engagement levels.

**Please read `FinalProjectReport.pdf` to see the final report with findings and conclusions.**

---

## Repository Structure

```
.
├── pictures/                 # Contains images and figures used in the report
├── .DS_Store                 # macOS system file (automatically generated)
├── .gitattributes            # Git attributes configuration file
├── .gitignore                # Git ignore file for API credentials
├── FinalProjectReport.pdf    # Final compiled PDF report with findings and conclusions
├── Main_Analysis.Rmd         # Main R Markdown file containing core analysis and report write-up
├── Main_Analysis.pdf         # Compiled main R Markdown file
├── README.md                 # This README file
├── Web_scraping.ipynb        # Jupyter Notebook used for scraping or final data cleaning steps
├── reddit_engagement_data.csv # Primary dataset containing Reddit comment metadata and text features
├── references.bib            # Bibliography file in BibTeX format for citations used in the report
```

## How to Compile and Run for Similar Personal Use

1. **Clone the Repository**  
   Open your terminal and run:
   ```bash
   git clone https://github.com/aaravg31/RedditAnalysis.git
   ```

2. **Install Required Packages**  
   Make sure you have the necessary packages installed. You can use the following commands for R and Python:

   **For R:**
   ```R
   install.packages(c("tidyverse",  "knitr"))
   ```

   **For Python:**
   ```bash
   !pip install -r requirements.txt
   ```

3. **Run the Web Scraper**  
   Open the `Web_scraping.ipynb` file in Jupyter Notebook and run all the cells to scrape data and generate the `reddit_engagement_data.csv` file.

4. **Run the Analysis**  
   Open the `Main_Analysis.Rmd` file in RStudio and knit it to produce the `Main_Analysis.pdf`. This file uses the dataset generated in the previous step to perform analysis and fit various models

---

## Acknowledgements

We would like to thank our DATA 410 instructor, Dr. John Thompson, for his valuable feedback and support throughout this project.
