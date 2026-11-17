# Python Job Listings Scraper

## Project Overview
This project uses Python web scraping to collect job listings from the Fake Python Jobs website.

## Objectives
Extract job information and organize it into a structured dataset.

## Technologies Used
- Python
- Jupyter Notebook
- Requests
- BeautifulSoup
- Pandas

## Data Collected
- Job Title
- Company Name
- Location
- Job Description Link

## Project Workflow
1. Fetch website HTML using Requests.
2. Parse HTML using BeautifulSoup.
3. Extract job titles, company names, locations and job links.
4. Store extracted records in a Python list.
5. Convert the data into a Pandas DataFrame.
6. Check missing values and duplicate records.
7. Clean text columns.
8. Export the final dataset into CSV format.

## Dataset
The project collected 100 job listings and saved them as `job_listings.csv`.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   `pip install requests beautifulsoup4 pandas`

3. Open `Job_Listing_Web_Scraper.ipynb` in Jupyter Notebook.
4. Run the notebook cells sequentially.

## Output
A CSV file containing 100 job listings with four columns.

## Project Page URL
(https://roadmap.sh/projects/job-listings-scraper/solutions?u=6adcbca8e41a25f41c921141)
