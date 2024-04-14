# Mars_HTML_Analysis
Challenge 11
## Scrape Titles and Preview Text from Mars News
- Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.
- Create a Beautiful Soup object and use it to extract text elements from the website.
- Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures giving each dictionary two keys: "title" and "preview". The preliminary scraping results show duplicates (due to extra white space) so I added a condition code that strips any extra whitespace characters from the title before checking duplicated titles.
## Scrape and Analyze Mars Weather Data
- Use automated browsing to visit the Mars Temperature Data Site. Inspect the page to identify which elements to scrape.
- Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
- Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
- Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate corresponding types.
- Conduct relevant analysis and export the DataFrame to a CSV file. One interesting fact is the methodology to approach calculating the terrestrial days exist in a Martian year. Since some terrestrial dates are "skipped", I made an assumption that each line item is 1 day which will results an additional column in my exported CSV file.
