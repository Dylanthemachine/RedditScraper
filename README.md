# RedditScraper
Date Created: 11/8/2021
Date Modified: 11/8/2021
Author: Dylan Jaramillo

Reddit scraper giving me the top results of my favorite subreddits and scanning for a specific keyword. In this case, it scans for the subreddits /r/judo, /r/bjj, and /r/sambo and searches by technique. It prints the URL so I can go to the page and check out the discussion of the technique. Otherwise, it prints a list of the hot 20 posts and saves them to a .csv I can look at. 

Frequently Asked Questions:  
1. Why is this a notebook?  This was originally developed on google colab. I wanted this to be able to run these on my two laptops without having to make sure the environments are the exact same and avoid using Docker
2. Why are limits and "sort by" hardcoded?  I am using this for one specific thing. Every other day, I browse these three subreddits for techniques I want to review before Jiu Jitsu. I can search for and find comments easily.
3. Can I steal these functions and make my own reddit scraper? Sure
