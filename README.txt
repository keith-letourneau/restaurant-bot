This function will allow a user to input what type of food they want to eat and where they are located. 

These user inputs are then placed into a search query URL in Yelp.

Using BeautifulSoup, the search query page will be web scraped for all URLs containing "/biz". 

These URLs will be placed into a list, and the first URL will be returned to the user. This URL will be a page for a recommended restaurant.

NOTE: Since this uses the BeautifulSoup module, it will have to be installed for this script to work. 

Python 3.8.3 was used to run this.
