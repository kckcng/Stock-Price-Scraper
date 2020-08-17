# Stock-Price-Scraper

> When evaluating GOOGLEFINANCE, Google Spreadsheets is not authorized to access data for exchange: 'SGX'

#### If `GOOGLEFINANCE()` fails you, this is the scraper for you.
<br/>

GOOGLEFINANCE() is a popular function on google spreadsheet for retrieving stock market data. However, some exchanges such as SGX, TYO and SHA are no longer supported. As mentioned [here](https://support.google.com/docs/forum/AAAABuH1jm0HDnOnJc8MRE/?hl=en&gpf=%23!topic%2Fdocs%2FHDnOnJc8MRE): 

> Due to issues beyond our control, the following exchanges are no longer supported in Google Sheets: TYO, INDEXTYO, BKK, INDEXBKK, SHA, INDEXCSI, SGX, & KLSE.
<br/>

To solve this problem, this scraper is created to help you retrieve stock market data in one click.

*****Please note that this scraper is designed to use on google drive only, along with a google spreadsheet for storing stock data.***

<br/>

## User Guide

1. Download the scraper to your google drive.

2. Create a google spreadsheet and input all the stock names you want to scrape in the first column (column A) starting from the second row (A2).

Example:

3. Open the scraper with google colaboratory.

4. Input the name of your google spreadsheet file at `google_sheet_name` and the sheet name at `sheet_name`.

5. Click the run button.

*You may need to authorize google to access your google drive. Just follow the instructions on the screen is fine.*
