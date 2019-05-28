# VoterListScraper

Voter List Scraper is a Python-based tool for scraping out Voters’ Information  from voter list(.pdf) to a csv file using regular expressions, zlib decompression.  The end product was later used as a source for Voter Search Engine which was developed six months down the line. 

# Requirements

This project requires Python, uses python standard library and doesn't require any additional library

# Run

python voterlistscraper.py source.pdf destination.csv

A pdf that was used at the time of building the scraper is included and can be scraped by entering the following command in command line -
python voterlistscraper.py voters.pdf somefilename.csv

This will generate a csv file named somefilename.csv which will contain the desired information.
