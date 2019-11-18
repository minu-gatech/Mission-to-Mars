# NASA-Mars

[Mars_Image](!Images/mission_to_mars.png)

## Objective: To scrape Mars following information from NASA website and render that scarped data into an HTML Page

  - NASA Mars News
  - JPL Mars Space Images - Featured Image
  - Mars Weather
  - Mars Facts
  - Mars Hemispheres

## Tools Used: Jupyter Notebook, Python, Pandas, Flask, Splinter, MongoDB, HTML, Bootstrap

### Tasks done to do scraping:
- Scraped the NASA Mars News Site and collect the latest News Title and Paragraph Text. ( https://mars.nasa.gov/news/ ) 
- Visited the url for JPL Featured Space Image and used splinter to navigate the site and find the full image url for the current Featured Mars Image ( https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars )
- Visited the Mars Weather twitter account and scrape the latest Mars weather tweet from the page. (https://twitter.com/marswxreport?lang=en)
- Visited the Mars Facts webpage and use Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc. (https://space-facts.com/mars/)
- Visited the USGS Astrogeology site to obtain high resolution images for each of Mar's hemispheres.(https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars)


