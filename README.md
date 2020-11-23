# Data-Science---Web-scraping

## The goal of this project is to get all the relationships of a multiple celebrities and return the output as a json file. 

## To run this file, you will need the following things:
1. collect_relationships.py
2. An empty directory
3. A json file consiting the name of the directory and all the names of the celebrities who's output we want (an example can be found in the repository)


## In the terminal, run the following command

python collect_relationships.py -c <config-file.json> -o <output_file>

## Required libraries:
1. BeautifulSoup
    to install beautifulsoup please run: pip install beautifulsoup4 in the command line
    
2. Pandas
    to install pandas please run: pip install pandas in the command line
    
3. requests
    to install requests please run: pip install requests in the command line
    
 
 The website use for scraping is: https://www.whosdatedwho.com/
        
