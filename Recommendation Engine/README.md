# CONTENT BASED MOVIE RECOMMENDATION SYSTEM!!
- Recommend Top 10 Similar Movies to the User depending on the Movie that the User Likes!!

# Table of Contents:
- Introduction
- Web Scraping in Python
- Technologies Used
- Launch
- Scope of Functionalities.
- Sources
- Conclusion

# Introduction
- A Content Based Movie Recommendation System, recommends Similar Movies to a User who likes a particular Movie, depending on the Characteristics of a the Liked movie by the user.
- Movies always Entertain us and as Humans, we always watch movies that someone highly recommends to us!!
- This Content Based Movie Recommendation system, analyses the various characteristics of the Movie that the User Likes and Recommends 10 similar movies to the User.


# Web Scraping in Python
- The Data Set Required For the Recommendation System is obtained by Scraping the information from the IMDb Website!
- Various Information about the movie such as:
    - The Name of the Film.
    - The Year of Release.
    - The Director of the film.
    - The Star and Overall Meta Score for the film.
    - The Genre that the film belongs to.
    - The Cast of the Film.

# Technologies Used
- Python is used to Scrape the Web Information.
- The Requests Library in python is used to get the contents of the webpage.
- The BeautifulSoup Library in Python is used to parse the contents as an HTML file.
- CountVectorizer class of sklearn library is used to vectorize the Strings available.
- Cosine Similarity method of metrics class of Sklearn is used to compute the similar scores between the vectors.


# Launch
- The requests library need to be installed in our local PC before the launch of this project.
- Install the library by the command [!pip install requests --upgrade --quiet]
- Install BeautifulSoup Library by the command [!pip install beautifulsoup4 --upgrade --quiet]

# Scope of Functionalities
- The movie Recommendation system can be used by the end user to obtain similar movies in accordance to his taste!!

# Sources
- https://www.imdb.com/feature/genre/?ref_=nv_ch_gr
- https://www.geeksforgeeks.org/
- https://towardsdatascience.com/

# Conclusion
- The Movie Recommendation System can be used to get recommendation for a user to watch similar movies!!


```python

```
