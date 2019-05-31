# MetroTwitter

Analysis of Twitter data in 13 English-speaking metropolitan areas (96K users and 180M tweets).

- US Cities (9): Atlanta, Austin, Bay Area, Boston, Chicago, Washington DC, LA, NYC, Seattle
- Australian Cities (2): Melbourne, Sydney
- Canadian Cities (1): Toronto
- UK Cities (1): London


Plus 223K users that aren't in these areas which are collectively put in 'Other'.

For more information, see the blog post:

[MetroTwitter - What Twitter reveals about the differences between cities and the monoculture of the Bay Area](https://huyenchip.com/2019/05/28/metrotwitter.html)

The blog post only contains a small, selected number of visualizations. For more visualization, download [here](https://drive.google.com/drive/folders/1B3rQeBhB50kdOCyNtwRhU26jO-F7VJAo?usp=sharing).

I won't be distributing the data for this project to protect users' privacy. If you'd like to discuss the data, contact me through my website [huyenchip.com](https://huyenchip.com).


## How people in different cities describe themselves
In the ``metrotwitter_visualization`` folder, you can find word clouds that represent the most popular words in bios in each city. The ``indi`` folder visualizes each city independently. The ``duo`` folder visualizes the difference between two cities.

<img src="images/london.png" width=700 align='middle'></img>
<img src="images/bay_area_nyc.png" width=700 align='middle'></img>

## What people in different cities talk about
In the ``metrotwitter_visualization`` folder, you can find word clouds that represent the most popular words in tweets in each city. The ``indi`` folder visualizes each city independently. The ``duo`` folder visualizes the difference between two cities.

<img src="images/bay_area_chicago.png" width=700 align='middle'></img>

## Ranking cities by popularity of keywords
In the ``keywords`` Jupyter notebook in this GitHub repo, there's the method ``rank_cities_by_keyword`` to visualize any keyword you want, either using ``bios`` or ``tweets``.

<img src="images/vc.png" width=700 align='middle'></img>
<img src="images/boba.png" width=700 align='middle'></img>

You can also plots multiple keywords on the same plot using the method ``rank_cities_by_multiple_keywords``. 

<img src="images/cities_by_keywords_social_tweets.png" width=700 align='middle'></img>

## Ranking keywords within a city
Also in the ``keywords`` Jupyter notebook, there's the method ``rank_keywords_in_city`` to rank the popularity of keywords within a city.

<img src="images/bay_area.png" width=700 align='middle'></img>

## Unique popular emojis in each city

<img src="images/emoji_1.png" width=600 align='middle'></img>

## Most unique city
<img src="images/unique_cities.png" width=700 align='middle'></img>

## Compare two keywords
Just to get a sense of how popular one vs another.
<img src="images/iphone_android.png" width=700 align='middle'></img>


