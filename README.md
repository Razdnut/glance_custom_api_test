# glance_custom_api
# Karakeep Custom API Widgets 

This repository contains two custom API widgets for Karakeep: 

     

   1 - Statistics Widget
    Returns statistics on the number of bookmarks and the number of tags. 
    
<img width="309" height="117" alt="immagine" src="https://github.com/user-attachments/assets/026f317c-b548-4ed1-adc2-ddabc0fa3562" />

     

   2- Recent Bookmarks Widget
    Lists the most recently added bookmarks. 
    
<img width="306" height="230" alt="immagine" src="https://github.com/user-attachments/assets/c4e5d5a4-0582-499b-bb56-c5f32ebb8f94" />
 
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



     
