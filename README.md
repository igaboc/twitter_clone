# README

# Database (DB)
## ERD (Entity Relationship Diagram)
[!ERD](/docs/db_schema.png)

# DB Tables
I made 3 tables for my app, User, Tweet and Profile. User stores the user information like password etc. Tweet stores the information message that a user tweets and the Profile tables stores information about the user. Each user has one profile and many Tweets.

## User Table
 - UserID
 - Email
 - Password

 ## Profile
 - First_Name
 - Last_Name
 - Country
 - UserID (belongs_to)
 - Avatar

 ## Tweet
 - TweetID
 - Message
 - UserID (belongs_to)

 # Pages
 ## homepage
 - show tweets on page
 - log in / log out

 ## tweet show page
 - see tweet
 - edit tweet (if logged in)

 ## profile page
 - First_Name, Last_Name
 - tweet count
 - avatar
 - country
 - edit ability


