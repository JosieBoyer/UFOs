# UFOs

---

## Project Overview

The core of this project was to build a dynamic webpage that filters a large table of data based on user input.  The purpose of the site is to aggregate and display data regarding sightings of UFOs.

---

## Results

### Deployed Web Application

Below is the basic layout of the index that displays when accessing the site.

![index_landing.png](https://github.com/JosieBoyer/UFOs/blob/main/UFOs-main/resources/index_landing.png)

### Filtering the Data

The user can filter the table results based on date, city, state, country, and shape (meaning the visual description of the sighting).  The filters can be reset by either refreshing the page or selecting the navigation bar at the top of the screen.  Multiple filters can be applied simultaneously, one at a time, or all at once. In the image below, the user has applied only one filter (by date).

![filter_by_date.png](https://github.com/JosieBoyer/UFOs/blob/main/UFOs-main/resources/filter_by_date.png)

To demonstrate individual functionality, here's an image of the table being filtered by city (Fresno), with no other filters:

![filter_by_city.png](https://github.com/JosieBoyer/UFOs/blob/main/UFOs-main/resources/filter_by_city.png)

To demonstrate functionality for multiple layered filters, the image below shows the table being filtered by state and shape (California, "Light"):

![filter_by_multi.png](https://github.com/JosieBoyer/UFOs/blob/main/UFOs-main/resources/filter_by_multi.png)

## Summary

- One drawback of this webpage:
    - Hitting "enter" while entering filter information will not execute the filter, but rather reset the page.

- Recommendations for future development:
    - Add drop down menus for certain search filters.  
    - Correct keyboard input so that "enter" will execute any filters that the user has entered.
