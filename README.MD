# Book Market Analytics: Books to Scrape

**Data Science 500 Assignment**
**Name:** [Pride Pafoule] | **Student ITS No:** [402603157]

## About this project

I scraped all 1,000 books from Books to Scrape (books.toscrape.com), cleaned the data, made charts to look for patterns, and built a linear regression model to predict book prices from rating, stock quantity and genre.

The main thing I found is that none of these features explain price. My model did no better than just guessing the average price. The website says its prices and ratings were randomly assigned, so this result is about this website and not about real book prices.

## Files

- `book_analysis.ipynb`: the notebook with everything, from scraping to modelling
- `books_dataset_raw.csv`: the data I scraped
- `books_dataset_clean.csv`: the cleaned data I used for the model
- `chart1` to `chart5` (PNG files): the charts


## How to run it

1. Install the libraries: `pip install requests beautifulsoup4 pandas matplotlib seaborn scikit-learn jupyter ipykernel`
2. Keep `book_analysis.ipynb` and `books_dataset_raw.csv` in the same folder.
3. Open the notebook, restart the kernel and click Run All.

Scraping takes about 10 minutes, so the notebook skips it if the raw CSV is in the folder. To scrape again, set `FORCE_RESCRAPE = True` in section 2.

## Videos that helped me

| Video | Channel | Link | What it helped me with |
|---|---|---|---|
| [Beatiful soup 4 tutorial #webscrapping] | [Tech with Tim] | [https://youtube.com/playlist?list=PLzMcBGfZo4-lSq2IDrA6vpZEV92AmQfJK&si=3zdCK_gBkOfXRDcI] | [what I learned  - how to scrape a basic html file and how to scrape a website that is online] |
| [matplotlib tutorial for beginners] | [Bro code] | [https://youtube.com/playlist?list=PLZPZq0r_RZONpa_Xg1MmyjmctJjL4l3Ay&si=mHmTNvmxWIdLSW6F] | [what I learned  - how to make a graph using the matplotlib library] |
| [Pandas tutorial for beginners] | [Bro code] | [https://youtube.com/playlist?list=PLZPZq0r_RZONoiL6kRbNM9nPiUM0eErWG&si=jvYBekyK4ImQmb4k] | [what I learned  - how to manipulate and analyse data] |

## Note

Books to Scrape is a practice website, so my results only apply to it.