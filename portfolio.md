---
layout: page
title: Portfolio
permalink: /portfolio/
---

### Projects




## Overwatch League Box Score [(link)](http://overwatch-live-stats.appspot.com/)

(React, Python, Selenium, Highcharts)

* Using Selenium, scraped data from a Twitch.tv extension every 5 seconds and stored them into a Mongo database.
* Compiled the data into JSON into a React SPA, creating an interface for people to check scores for each match and infographics.
* Still working being able to make comparisons between different matches without having to load all the information.


![filtered](/images/box_score.png)
A box score between the Los Angeles Gladiatiors and the Boston Uprising.

![teamfight](/images/graph.png)
A graph showing the eliminations per minute in a map.



## Teamfight Viewer for Overwatch League [(link)](https://teamfightviewer.herokuapp.com/)

(React, Python, OpenCV)

* A webapp that took raw stats from Overwatch League, a competitive gaming league, and parsed out just key stats and fights into an easy to understand UI
* Extracted key objectives and key team fight statistics from gameplay video using OpenCV
* Displayed location and relevant details of each key fight on a react based GUI that shows events overlayed on a map.

![filtered](/images/original.png)
Starting with this image
![colored](/images/filtered.png)
After color filtering
![colored](/images/map.png)
Points placed onto the map
![teamfight](/images/teamfight.png)
A peak of the website UI.


## Competitive Genji Blog [(link)](https://medium.com/@Cheraws/what-stats-make-the-best-genji-blades-in-owl-1e7496c7bb45)

(Tableau, Scrapy, Python)

* Made a numerical analysis of Pro Genji(type of character in overwatch) players using extracted Overwatch League stats and wrote about key findings on Medium
* Reverse engineered Winstons Lab, a Overwatch Stats website, to get data for the analysis
* Used Tableau to point out  anomalies/correlations in the data with clear graphs

![teamfight](/images/tableau.png)
A screenshot of Genji statistics.

## Analysis on how Mains Affect the Overwatch Meta [(link)](https://passintotheiris.herokuapp.com/)
(Tableau, Scrapy, Python)

* Created a blog from the ground up using Node, React, and MongoDB 
* Scraped stats from overlog.gg into MongoDB to be used by the blog
* Graphed key findings using chart.js

![An example graph of what I showed in chart.js](/images/pie.png)





