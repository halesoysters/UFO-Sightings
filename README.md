# UFO-Sightings
Javascript


![header](images/ufos.png)

## Overview

This project primarily uses HTML and JavaScript to create an interactive webpage that takes information entered by the user - properties in the Document Object Model (DOM) - to parse and return back queries from the object 'data' on UFO sightings.  

**View the page at:**  https://halesoysters.github.io/

## Results

Users enter search criteria such as city, state or shape into the webpage.  The following HTML code creates the container that holds the list item class, or attribute, that users will type into:

![header](images/filter_search.png)  ![header](images/filter_code.png) 

Through the `d3.selectAll()` function, when a change takes place to the HTML DOM element with the id tag, the function function updateFilters() is triggered:

![header](images/conlsole_log.png) 


## Summary

One obvious drawback is that the data is case sensitive.  Given more time, I could have used the Python function `str.lower()` to transform the string data being entered by users into lowercase.  
