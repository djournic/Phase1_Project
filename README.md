# Movie Data Analysis
## Introduction
This is my repository for the Phase 1 Project for the Flatiron School. This project involves analyzing movie data to create recommendations for a hypothetical movie being produced
by Microsoft. I used some simple web scraping and data cleaning to get the data I needed to make my case.

## The Problem
Disney has made over 900 kajillion dollars with the MCU and Microsoft wants to be a part of the action (that number may not be accurate as of the time of posting). So I have been
tasked with recommending what movies Microsoft should make when getting into the business.
There are a lot of elements to look at regarding movies and what makes them successful or not. To keep it simple, I looked at money, also assuming Microsoft would be interested in making money.


![Alt text](https://tenor.com/view/shut-up-take-my-money-gif-6068097.gif)

## The Data
The project provided a number of files to read, which I did. These included numbers from IMDB, and Box Office Mojo. I then decided I wanted other(and better) data, so I did some web scraping from Wikipedia and TheNumbers. I got plenty of more relevant data for the recommendations I wanted to make. 
I came to the conclusion early on that sequels were the simplest answer to how to make money making movies. The majority of the movies were sequels, and not just the first sequel, many were the 3rd or higher in the series.
I went a little further into sequels, looking at the highest grossing sequels, and again most were the 3rd or higher.
Then I went into video game movies, from Box Office Mojo, the 10 highest grossing video game movies. I was pleased to see that 2 of the Resident Evil movies were there.
This led me to look deeper into that series, and graphed how each movie made more money than the previous (with 1 exception).
I then compiled some data from Microsoft's video game franchises, and saw how much they were worth.

## The Process
Like I mentioned earlier, a good bit of web scraping was done to get the data I wanted. Then using Pandas methods to clean the data and get it into a useable form. Then Matplotlib to create some visualizations to help drive the point home.
At this point I was prepared to turn in the project. I made my powerpoint presentation, this repository, etc. And made my first presentation

After the initial presentation, I was advised to get some more data, specifically genre data as well as a "large" dataset. So the revisions were my attempt to comply.
I was tasked with getting an aspect of the movies, and looking at that. So I picked genre, found some data on how much each genre has made, as well as the number of movies produced, graphed that.
I was also tasked with parsing data from a large dataset, I found the file mentioned below. I merged it with one of the datasets provided, and got it down to a manageable number.

There is a dataset I could not fit on this repository, title.akas.tsv.gz, it's located here:
https://datasets.imdbws.com/

# Conclusion
As an initial project, introducing myself to Data Analysis and its various methods, this went really well. If Microsoft wanted to make movies, making a series about Halo seems like a no-brainer; there are so many stories that can easily be made into movies and the franchise is insanely popular. They only need to commit to making multiple movies, since I've shown that sequels almost always do better.
