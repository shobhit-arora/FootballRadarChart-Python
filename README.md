# Football_DataScraping_RadarChart-Python

Made a jupyter notebook to plot radar charts by scraping data from fbref.com.

Fbref has a table with a lot of statistics, called a scouting report that looks like this:

![FbrefTable](https://user-images.githubusercontent.com/47402718/134780105-59961251-d101-46ff-be6c-9c3f105a3d5d.jpg)

This data has been scraped using the BeautifulSoup library

Then a radar chart has been made using the Python library called mplsoccer and matplotlib:

The chart for a player called Bruno Fernandes looks like this:

![RadarBruno jpg](https://user-images.githubusercontent.com/47402718/134779957-ff49907c-015a-412e-8740-0d7e7dcbff6c.png)


In this chart 20 different parameters have been plotted against the highest value when compared with other midfielders.
So a player's best and worst attributes can be seen all at once.

This chart can also be used to compare different players of same profile, acting as a very good visual comparison chart.
