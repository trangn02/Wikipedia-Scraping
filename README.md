# Wikipedia-Scraping
This project, Wikipedia Scraping, is a Python-based program that aims to scrape a Wikipedia page for tabular data and represent it in a bar graph. Wikipedia Scraping also involves numerous tools such as extracting, transforming, and loading raw data, all skills that are essential in the handling of unprocessed, raw data. Gathering descriptive statistics and exporting data into files such as .csv files is also explored in Wikipedia Scraping. Through Wikipedia Scraping I hope to make the act of extracting data from wikipedia as accessible and reproducible as possible. 

The libraries used to extract the data and parse through the html files are BeautifulSoup, pandas, and requests. The libraries used for the visualization are numpy, scipy, and motplotlib.

There are various data types and attributes within Wikipedia Scraping, which are including but not limited to:
1. lists (lists of lists, tables, `table_data`, `raw_data`) 
2. indices (integers, `column_1`, `column_2`, `[3]`)
3. visualization labels (strings, integers, `xlabel`, `ylabel`, `title`)
4. html objects (strings, `html.parser`)

Biases: The largest bias issue that needs consideration is dealing with the source, Wikipedia. Wikipedia can be edited by users online and relies on volunteers to craft the data, which leaves it vulnerable to manipulation with negative intent. This may mean that not every Wikipedia page contains completely accurate information, which may lead to skewed, unreliable data. 

This project is licensed by the MIT License. https://opensource.org/license/mit/

Acknowledgments:
- Beautiful Soup (for HTML Parsing)
- pandas (for data analysis)
- requests (for HTTP requests)
- numpy (for numerous mathematical operations)
- matplotlib (for creating visualizations from data)
