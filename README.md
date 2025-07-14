# glance_custom_api
# Karakeep Custom API Widgets 

This repository contains two custom API widgets for Karakeep: 

     

   1 - Statistics Widget
    Returns statistics on the number of bookmarks and the number of tags. 
     

   2- Recent Bookmarks Widget
    Lists the most recently added bookmarks. 
     
# About Me 

I am not a developer or programmer. Most of the work was done using ChatGPT, with some manual corrections to the API call syntax.

# Variables: 

     

    ${KARAKEEP_URL} = karakeep.domain.com
    (If you connect via localhost, remember to change the connection protocol from https to http.) 
     

    ${KARAKEEP_API_KEY} = Your API key generated in Karakeep. 
     


## Options

| Option          | Description                                   | Values             |
|-----------------|-----------------------------------------------|--------------------|
| `limit`         | Number of latest bookmarks to list            | 10, 20, or 30      |
| `in-new-tab`    | Open links in a new browser tab                | `true` or `false`  |
| `collapse-after`| Collapse list after this many items            | Integer (e.g. 5,10)|
     
