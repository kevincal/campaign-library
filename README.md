#Campaign Library

This is a open source project to create the largest digital archive of political campaign videos
ranging from advertising, endorsements, and debates.  The goal of this project is to create a
historical digital media mosaic around a political figure and to eventually be able to track
and measure the evolution of positions over time.  It is optimistic.

##Current State

Current implementation of this project is utilizing a python 2.x based open source platform called 
[Media Drop](https://github.com/mediadrop/mediadrop) hosted on Google App Engine.

##Future State
* Video Aggregation Tools to auto-archive web-content
* Image ML to auto-attribute video content

##Requirements 

1. Python 2.x
2. [git-subrepo](https://github.com/ingydotnet/git-subrepo)

##Installation Steps

    # Get Project
    git clone https://github.com/kevincal/campaign-library

    # Create a new virtual environment:
    cd campaign-library
    virtualenv --python=/usr/bin/python2.7 --distribute --no-site-packages venv

    # Now, activate that virtual environment:
    source venv/bin/activate
