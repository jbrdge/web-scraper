# web-scraper(s)

## Notebooks Include:

### 1) mlk_speech_parser
This project is a walkthrough from AnalystBuilder:
This is a basic web scraper that pulls a martin luther king jr speech and cleans the string returned.  
website: "http://analytictech.com/mb021/mlk.htm"  

First, the data is loaded and transformed to a single string:  
<p><img src="https://raw.githubusercontent.com/jbrdge/web-scraper/main/img/mlk_speech_to_string.png" width="65%"></p>  

Then, we tested basic functions, including count occurance per word:
<p><img src="https://raw.githubusercontent.com/jbrdge/web-scraper/main/img/mlk_speech_wordcount.png" width="65%"></p>  



### 2) data_table_parser
This project is a walkthrough from AnalystBuilder:
This pulls data from a website and reconstructs the inlaid table as a pandas dataframe.  
website: "https://www.worldometers.info/coronavirus/population-by-country/"

The goal here was to practice scraping a data table from a website:  
<p><img src="https://raw.githubusercontent.com/jbrdge/web-scraper/main/img/original_table.png" width="65%"></p>  

Then, we convert the table in to a pandas DataFrame:
<p><img src="https://raw.githubusercontent.com/jbrdge/web-scraper/main/img/pandas_dataframe.png" width="65%"></p>  

First, the data is loaded and transformed to a single string:  
<p><img src="https://raw.githubusercontent.com/jbrdge/web-scraper/main/img/mlk_speech_to_string.png" width="65%"></p>  

Most of the heavy lifting was done here in the code. It finds each row (excluding the header), then creates a list of each column for that row. And finally, appends that to a previously created DataFrame that existed only of the header at this point:
<p><img src="https://raw.githubusercontent.com/jbrdge/web-scraper/main/img/mlk_speech_wordcount.png" width="65%"></p>  

