# Just Watch WebScrapping Analysis
Scrapped movies and TV shows data from the Just Watch, performed analysis and created wordcloud visualisation
This project includes, webscraping using BeautifulSoup from the website JustWatch. JustWatch is a popular platform that allows users to search for movies and TV shows across multiple streaming services like Netflix, Amazon Prime, Hulu, etc.

## **Overview**
The tasks performed in this project are as follows:-
### **Tasks:**

**1. Web Scraping:**

Used BeautifulSoup to scrape the following data from JustWatch:

   **a. Movie Information:**

      - Movie title
      - Release year
      - Genre
      - IMDb rating
      - Streaming services available (Netflix, Amazon Prime, Hulu, etc.)
      - URL to the movie page on JustWatch

   **b. TV Show Information:**

      - TV show title
      - Release year
      - Genre
      - IMDb rating
      - Streaming services available (Netflix, Amazon Prime, Hulu, etc.)
      - URL to the TV show page on JustWatch

  **c. Scope:**

```
 ` - Scrapped data of 100 movies and 100 TV shows including NA values.
   - The chosen entry point was popularity filter to ensure a diverse dataset.`

```


**2. Data Filtering & Analysis:**

   After scraping the data, I used Pandas to perform the following tasks:

   **Data Analysis:**

   ```
      - Calculated the average IMDb rating for the scraped movies and TV shows.
      - Identified the top 5 genres that have the highest number of available movies and TV shows.
      - Determined the streaming service with the most significant number of offerings.
      
   ```   

**3. Data Export:**

```
   - Exported the filtered and analysed data into an Excel file for further processing and reporting.
   
   - It included the created dataframes in different sheets, performed with the help of openpyxl.

   - Saved the excel file in google Drive Folder.


## **Liabraries**
 - Requests
 - bs4, BeautifulSoup
 - Numpy
 - Openpyxl
 - wordcloud
 - Matplotlib
 - Pandas