# On the Road: Fan Insights for Touring Artists, via Twitter

## Summary

Inspired partly by my days as a touring musician and partly by Spotify for Artists, I synthesized multiple data sources to uncover geo-targeted fan trends for touring artists. 

As a real-world test case, I acquired Twitter mentions for all bands on a label called XL Recordings going back to the end of May 2017.  After cleaning up user profiles, I obtained latitude-longitude coordinates via the Google Maps API, and mapped tweets to an interactive dashboard using Python for Plotly. 

Finally, I overlaid county population estimates to illustrate the fact that touring artists should capitalize on high user engagement in less-populated areas. 

This was presented as my final passion project at Metis, a data science immersive bootcamp in New York City. 

## Repo Contents:

- IPython Notebooks 
- Final presentation
- Visualizations
- Interactive visualizations on Plotly here and here

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

