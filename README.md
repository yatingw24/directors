# Can Women Make Hollywood Blockbusters? A data analysis on gender disparity among female- and male-directed films

Here is the shortcut to my [article:](https://yatingw24.github.io/directors)

Data:
- [BBC: The 100 greatest films directed by women](http://stats.customs.gov.cn/indexEn)
- [BBC:The 21st Century’s 100 greatest films](https://www.bbc.com/culture/article/20160819-the-21st-centurys-100-greatest-films) 
- [IMDb](https://www.imdb.com/)
- [Box Offical Mojo](https://www.boxofficemojo.com/)

## Key Takeaways 


## What I Did:
### Tech Stack sed:
 - `python - pandas`
 - `Datawrapper`
 - `JavaScript`
 - `R`
 - `ai2html`

### A Break Down of Files:
1. notebooks:

 - `scraping.ipynb`: data scraping on two BBC lists of films and merging with IMDb hyperlinks.
 - `mojo.ipynb`: merging two BBC lists with financial records from Box Office Mojo.
 - `Analysis.ipynb`: data analyses on awards/nominations, ratings, and the financials. 

2. spreadsheets:
 - `boxoff.csv`: worldwide box office for each film. 
 - `feamles_list_bbc.csv`: best films directed by women filmmakers and their rating, nominations, award and genres. 
 - `genre_share.csv`: the share of each genre within each gender's list. 
 - `list_all_bbc.csv`: best films directed by male filmmakers and their rating, nominations, award and genres. 
 

3. charts/graphics:
 - `ai2html-output`: responsive bee swarm charts.
 - `ai2html-output-bar`: responsive bar charts. 

### Data Cleaning and Analysis
1. Comparison of critical reception between female- and male-directed films.
- scraping: titles, directors, and publication years from two BBC lists;
- merging: with IMDb’s film metadata, collecting hyperlinks, ratings, award wins, nominations, and genre
- statistical test: by running a linear regression, I found a weak positive correlation between the number of awards won by a film and its rating.
- analyzing gender difference in genre tags: by mapping each individual or niche genre tag to a broader category and calculating the share of a certain genre with each list, I aim to understand what type of stories female vs. male directors dominate. 

2. Comparison of box office performance between female- and male-directed films.
- scraping: titles, directors, and publication years from two BBC lists;
- merging: with Box Office Mojo's metadata, collecting the worldwide gross revenue
- visualizing distribution: with a bee swarm chart, it is easier to see the gender gap in box office and the outliers. 


### Liminations & Potential Improvements






