# TrueLayer
An Assessment on a simple command line application that would output to STDOUT the top posts in JSON from https://news.ycombinator.com.

# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

# Prerequisites
PyCharm
python 3

Create a new project in Pycharm along with a virtualenv.
Install the following libraries:
BS4 - Beautifulsoup, for scraping data from the url
Requests
pandas - to save the results in a dataframe
maths - mathematical functions

# Instruction
In order to make it more fun to read for robots (and easier to integrate in our workflow) we would like to write a simple command line application that would output to STDOUT the top posts in JSON. 

Output format
[
    {
        "title": "Web Scraping in 2016",
        "uri": "https://franciskim.co/2016/08/24/dont-need-no-stinking-api-web-scraping-2016-beyond/",
        "author": "franciskim",
        "points": 133,
        "comments": 80,
        "rank": 1
    },
    {
        "title": "Instapaper is joining Pinterest",
        "uri": "http://blog.instapaper.com/post/149374303661",
        "author": "ropiku",
        "points": 182,
        "comments": 99,
        "rank": 2
    }
]

Input arguments
We expect the application to take these arguments:
hackernews --posts n
--posts how many posts to print. A positive integer <= 100.

