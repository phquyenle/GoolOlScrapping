# GoolOlScrapping
In this assignment, you'll create a web app that lets users view and leave comments on the latest news. But you're not going to actually write any articles; instead, you'll flex your Mongoose and Cheerio muscles to scrape news from another site.

# Instructions


Create an app that accomplishes the following:


Whenever a user visits your site, the app should scrape stories from a news outlet of your choice and display them for the user. Each scraped article should be saved to your application database. At a minimum, the app should scrape and display the following information for each article:


Headline - the title of the article


Summary - a short summary of the article


URL - the url to the original article


Feel free to add more content to your database (photos, bylines, and so on).




Users should also be able to leave comments on the articles displayed and revisit them later. The comments should be saved to the database as well and associated with their articles. Users should also be able to delete comments left on articles. All stored comments should be visible to every user.




Beyond these requirements, be creative and have fun with this!



# Tips


Whenever you scrape a site for stories, make sure an article isn't already represented in your database before saving it; Do not save any duplicate entries.


Don't just clear out your database and populate it with scraped articles whenever a user accesses your site.

If your app deletes stories every time someone visits, your users won't be able to see any comments except the ones that they post.




# Helpful Links

MongoDB Documentation
Mongoose Documentation
Cheerio Documentation

# How the app should look like
![](public/assets/images/2.jpg)
![](public/assets/images/1.jpg)
