# Data-Collection-challange

In this project, I identified HTML elements on a webpage and utilized this knowledge to extract information through both automated browsing with Splinter and HTML parsing with Beautiful Soup.
This project is divided in two parts: 

-	part 1: Scrape titles and preview text from Mars news articles.

-	part 2: Scrape and analyze Mars weather data, which exists in a table.

# Part 1: Scrape Titles and Preview Text from Mars News
Using Jupyter Notebook to visit the Mars news site and inspected the page to identify which elements to scrape. Subsequently, I created a Beautiful Soup object and utilized it to extract text elements from the website. After extracting the titles and preview text of the news articles, the code stored the scraping results in Python data structures. Each title and preview text pair was stored in a Python dictionary with two keys: 'Title' and 'Preview'. Finally, the code exported the scraped data into a JSON file.

# Part 2: Scrape and Analyze Mars Weather Data
Using Jupyter Notebook, I developed code to scrape and analyze Mars weather data. Employing automated browsing, I visited the Mars Temperature Data Site Links and inspected the page using Chrome DevTools to identify the elements for scraping. The code then saved the information into a DataFrame, leveraging this data to address specific questions:
How many months exist on Mars?
![Mars_temperature_averaged](https://github.com/MarcoN16/Data-Collection-challange/assets/150491559/70a9081a-3d70-4701-8e34-7ac0283e6fcc)


What are the coldest and warmest months on Mars (at the location of Curiosity)?
![Mars_temperature_averaged_sorted](https://github.com/MarcoN16/Data-Collection-challange/assets/150491559/be0fd644-9b17-4080-bd38-5a70d003a060)


Which months have the lowest and highest atmospheric pressure on Mars?
![Mars_pressure_averaged](https://github.com/MarcoN16/Data-Collection-challange/assets/150491559/1a115427-1c06-456d-86ae-b60bf075bd3b)


How many Martian (and not Earth) days' worth of data exist in the scraped dataset?
![Mars_terrestrial_days](https://github.com/MarcoN16/Data-Collection-challange/assets/150491559/4892beef-1d6b-4d1c-84af-601af9c612a8)


Finally, the DataFrame was exported to a CSV file for further analysis.

