# Exploring-Hacker-News-Posts

This project involves analyzing posts from Hacker News, a popular site for technology-related discussions, to compare two types of posts: Ask HN and Show HN. Our goal is to determine:

Whether Ask HN or Show HN posts receive more comments on average.
If the time a post is created impacts the average number of comments it receives.

## Project Overview

## Dataset

The dataset used in this project contains approximately 20,000 rows, reduced from the original 300,000 by removing submissions without any comments and randomly sampling from the remaining data. The data includes various attributes like the post title, the time it was created, and the number of comments it received.

## Steps Involved

**1. Introduction:**

We start by reading the data and removing any headers to prepare it for analysis.

**2.Extracting Ask HN and Show HN Posts:**

We filter the dataset to isolate posts that start with "Ask HN" and "Show HN" to focus our analysis on these two types of posts.

**3.Calculating the Average Number of Comments for Ask HN and Show HN Posts:**
 
 We calculate the average number of comments for both Ask HN and Show HN posts to determine which type generally receives more engagement.

**4.Finding the Number of Ask Posts and Comments by Hour Created:**

We then analyze Ask HN posts to determine the distribution of posts and comments by the hour they were created.

**5.Calculating the Average Number of Comments for Ask HN Posts by Hour:**

This step involves finding out the average number of comments Ask HN posts receive based on the hour they were created.

**6.Sorting and Printing Values from a List of Lists:**

Finally, we sort and display the results to identify the optimal time to post on Hacker News to maximize comments.

## Conclusion

The analysis suggests that Ask HN posts receive more comments on average than Show HN posts. Moreover, the most active period for receiving comments on Ask HN posts is between 15:00 and 16:00 EST (3:00 PM - 4:00 PM EST).

However, it's important to note that the analysis only considered posts that received at least one comment. Therefore, the conclusion is more accurately stated as: Of the posts that received comments, Ask HN posts received more comments on average, and Ask HN posts created between 15:00 and 16:00 EST received the most comments on average.

## Repository Contents
- hacker_news_analysis.ipynb: The Jupyter Notebook containing the code and analysis for this project.

- hacker_news.csv: The dataset used for the analysis, after filtering out posts without comments.

- README.md: This README file providing an overview of the project.

 ## Requirements
- Python 3.x

- Jupyter Notebook

- Libraries: pandas, numpy, matplotlib
