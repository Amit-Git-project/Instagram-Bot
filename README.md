# Instagram Automation with Selenium
This repository contains Python scripts using Selenium to automate various tasks on Instagram. Each script addresses a specific problem statement related to interacting with Instagram's interface.

Problem Statements and Solutions
Problem 1: Login to your Instagram
Login to your Instagram handle using sample username and password.

Problem 2: Search for "food" in the search bar
Search for "food" in the Instagram search bar and print the names of displayed handles (excluding hashtags).

Problem 3: Search and open a profile
Search for and open the profile of "So Delhi".

Problem 4: Follow/Unfollow a given handle
Open the Instagram handle of "So Delhi".
Follow it and print a message if already following.
Unfollow the handle and print a message if already unfollowed.
Problem 5: Like/Unlike posts
Like the top 30 posts of 'dilsefoodie' and print a message if already liked.
Unlike the top 30 posts of 'dilsefoodie' and print a message if already unliked.
Problem 6: Extract list of followers
Extract the usernames of the first 500 followers of 'foodtalkindia' and 'sodelhi'.
Print the followers of 'foodtalkindia' whom you follow but don’t follow you.
Problem 7: Check the story of 'coding.ninjas'
Check the story of 'coding.ninjas' and handle these scenarios:

Print an error message if you have already seen the story.
Print an error message if the user has no story.
View the story if not yet seen.


# Instagram Analytics with Selenium

This repository contains Python scripts utilizing Selenium for Instagram automation. The projects below address specific analytics tasks related to Instagram handles and hashtags.

## Project 1: Analyzing Food Bloggers' Habits

### Task 1: Analyzing Followers and Posts
- Open the first 10 handles obtained from searching 'food' and determine the top 5 handles with the highest number of followers.
- Find the number of posts these top handles have made in the previous 3 days.

### Task 2: Visualization using Graphs
Depict the information gathered above using a suitable graph.

## Project 2: Hashtag Analysis for Posts

### Task 1: Scraping Post Content
- Access the 5 top handles from the previous task and scrape the content of their first 10 posts each.
- Compile a list of words used in these posts and calculate their frequencies.

### Task 2: Generating a CSV File
- Create a CSV file containing two columns: the word and its frequency.
- Identify the most popular hashtags used among these bloggers.

### Task 3: Visualization using Charts
Plot a Pie Chart showcasing the top 5 hashtags and the frequency of their usage by the bloggers in the scraped posts.

## Handle Analytics: Followers to Likes Ratio

### Task 1: Calculating Likes
- Determine the likes received on the top 10 posts of the 5 handles acquired earlier.
- Calculate the average likes for each handle.

### Task 2: Calculating Ratio
- Derive the average followers:likes ratio for each handle by dividing the average likes by the number of followers.
- Represent this information using a bar graph.
