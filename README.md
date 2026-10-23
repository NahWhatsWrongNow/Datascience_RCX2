# DATA SCIENCE 500 BOOK MARKET ANALYTICS

Automatic Scraper Beta Build

402420737
Jadon Govender
Data Science 500

## 1

My initial idea was rather simple, fork the scraper provided and make my own changes, then create an automatic graph and PDF maker, to do this i had to map out a **TON** of variables then recall them during processing using "Fig's Importer Tools" as inspiration I made a pdf crafter that first makes graphs, then screenshots them, then uses a template of word I provided to it and converts values based on scraper info, I also made an auto installer!

Over 112 different libraries were used in the making of this project...



## How 2 Run on Windows (updated build)

1. Install Python **3.10 or newer** with **Add Python to PATH** enabled.
2. Extract `402420737_Datascience500` and open the folder.
3. Run `SETUP_WINDOWS.bat` to install the required Python packages.
4. Run `START_NOTEBOOK.bat` and open `Book_Market_Analytics.ipynb` in JupyterLab.
5. Select **Run > Run All Cells**. `SOURCE_MODE = 'live'` collects the catalogue from Books to Scrape and generates the graphs, dataset, and reports.
6. The cleaned dataset is written to `books_cleaned.csv`, and the PDF to `Book_Market_Report.pdf` in the main folder.
7. The document template is at `autopdf/Report_Template.docx`. The generated editable Word report is saved to `autopdf/Book_Market_Report.docx`.
8. `SOURCE_MODE = 'preview'` uses the included 2021 archive dataset for a local run.
9. PDF conversion uses Microsoft Word or LibreOffice.

## 3. Exploratory analysis.

Coded for Each graph to use a distinct main colour for visual analysis, then statistical values are compared resulting in a value which is returned under a premade template in a place during PDF creation after a phrase, however if certain values change the text on the pdf will update to version that makes itself true, so if you had a cat is a animal that is a true statement however anything that isnt an animal would make that statement false hence why I decided to make 2 versions of the template, one with true text for true values and 1 for negative text with negative values, returning either version and inserting the value after it!

## 4. Github
https://github.com/NahWhatsWrongNow/Datascience_RCX2