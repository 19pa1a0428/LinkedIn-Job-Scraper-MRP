# LinkedIn-Job-Scraper

Run search_retriever.py to find new job postings and insert most recent ids to db

Run details_retriever.py to populate table with individual job api call

While search_retriever.py should not cause any problems even through your personal IP and a singular account, ```details_retriever.py``` can be finicky since every search yields ≈25-50 results, which all need to be called individually to obtain their attributes. I recommend using multiple proxys and accounts with ```details_retriever.py``` and try playing around with the delay.  
