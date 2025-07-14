# glance_custom_api
Karakeep Custom API Widgets 

This repository contains two custom API widgets for Karakeep: 

     

   1 - Statistics Widget
    Returns statistics on the number of bookmarks and the number of tags. 
     

   2- Recent Bookmarks Widget
    Lists the most recently added bookmarks. 
     

Setup 

You need to set the following variables: 

     

    ${KARAKEEP_URL} = karakeep.domain.com
    (If you connect via localhost, remember to change the connection protocol from https to http.) 
     

    ${KARAKEEP_API_KEY} = Your API key generated in Karakeep. 
     

Options 

     limit: Number of latest bookmarks to list (10, 20, or 30)  
     in-new-tab: true or false (whether to open links in a new tab)  
     collapse-after: Collapse the list after this many items
     
