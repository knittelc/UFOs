# UFOs

## Overview
 Create a webpage and dynamic tabletable with filters for the date, city, state, country, and shape using JavaScrip E6+ and HTML.  Dana has been asked to use data from UFO sightings across the United States to pull into this interactive table.  I also created the intro to the web page, tie in a relavent article for support, and then present the table.
 
## Resources
- JavaScript version ES6+
- HTML5
- Bootstrap
- CSS

## Results
-Usage
 The landing page pulls up a navigation bar (which reloads the page), the header/title, the article title and article splitting the screen, and finally by scrolling down; the table comes into view.  
![page landing](https://user-images.githubusercontent.com/102183530/174441624-67b9496c-caca-4fa6-95ac-f46e964c5170.png)

- Design Elements
 When the filter and table are in sight, the user is able to filter by any one or multiple categories.  Here are examples of a state and country filter, then a shape filter.  Upon entering the desired filter text, a hard 'enter' initiates the filter of the data.
![filter state and country](https://user-images.githubusercontent.com/102183530/174441667-5799665b-5055-4c81-8816-9fbab2e24b60.png)

![filter by shape triangle](https://user-images.githubusercontent.com/102183530/174441671-90052658-6baa-41ac-83f6-ae16ca70233a.png)

 I would also show a filter by date possible, but as all the data are from the same date, while knowing 'HOW' to set this filter, it is sort of useless with this data.  This limitation is discussed below.
 
## Summary

### Improvements and Limitations

- Some of the drawbacks of this type of filters, are that the user would need to actually know what the options are already by scrolling all the way through the data, thus negating the usefulness of a filter.  A better idea would be a predictive or filter in filter use.  So, if the user were to type a 'C' for the state options only the 'c' options would present themselves.  The "shape" category could use a little help.  Not many people would know to look for 'round' vs 'circle', and 'light' is not a shape inherently known for usage in this instance.
- This data set is also very limited and all the dates are the same.  A larger study of global ufo spottings would lend itself to more credibility.  
This could be tied to a google map, which could help show trends in spottings of ufos.  The map could also be filtered based on what the criteria of the filter is showing.  The map could hone in on specific areas or stay global if the date is used as a filter first, which could also show the activity for a year globally.
- Another additive feature could be to gather more information by scraping through the comments.  Some of these are very simliar and add more information to the entire scope of the reported sightings.
