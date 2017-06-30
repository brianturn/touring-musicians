# On the Road: Fan Insights for Touring Artists, via Twitter

## Summary

Inspired partly by my days as a [touring musician](https://open.spotify.com/artist/2umvffrPSrINnWYTrrJFAx?play=true&utm_source=open.spotify.com&utm_medium=open) and partly by [Spotify for Artists](https://artists.spotify.com/), I synthesized multiple data sources to uncover geo-targeted fan trends for touring artists. 

As a real-world test case, I used the Twitter API to acquire mentions for all bands on an independent record label called [XL Recordings](www.xlrecordings.com/), going back to the end of May 2017.  After cleaning up user profiles, I obtained latitude-longitude coordinates via the Google Maps API, and mapped tweets to an interactive dashboard using Python for Plotly. 

Finally, I overlaid [county population estimates](https://www.ers.usda.gov/data-products/county-level-data-sets/) to illustrate the fact that touring artists should capitalize on high user engagement in less-populated areas. 

This was presented as my final passion project at [Metis](https://www.thisismetis.com/), a data science immersive bootcamp in New York City, in June 2017. 

## Repo Contents:

- IPython [Notebooks](https://github.com/brianturn/touring-musicians/tree/master/notebooks) 
- [Final presentation](https://github.com/brianturn/touring-musicians/blob/master/presentation/turner_brian_presentation_final.pdf)
- [Visualizations](https://github.com/brianturn/touring-musicians/tree/master/images)
- Interactive visualizations on Plotly [here](https://plot.ly/~brianturn/9.embed) and [here](https://plot.ly/~brianturn/11.embed)

## Tools

- Python nltk
- Vader sentiment analysis
- Amazon Web Services
- Pandas
- Plotly
- Matplotlib

## Data 

- Twitter API - 200,000 tweets
- Google Maps Geocoding API
- USDA economic research population estimates

