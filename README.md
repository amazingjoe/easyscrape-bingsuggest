# EasyScrape-BingSuggest

Scrape Bing Searchbar Suggested Terms

<img src="https://github.com/amazingjoe/amazingjoe.github.io/blob/main/imgs/Easyscrape.png" width="50%"/>

## Instructions

1. Install:

```
pip install easyscrape-bingsuggest
```

2. Get Bing Suggestions for a Search Term:

```python
from easyscrape_bingsuggest import querysuggestions as BS

# Request suggestions for a search term
BSResults = BS.query("Monty Python")
BSResults

['Monty Python', 'monty python', 'monty python and the holy grail', 'monty python movies', "monty python's flying circus", 'monty python cast', 'monty python spam', 'monty python life of brian', 'monty python quotes']
```

3. BS.query returns a list of strings with the results.