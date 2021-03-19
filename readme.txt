Module Name : mymodule
mymodule is developed using Drupal 8.9 

Features of mymodule
 - Create siteapikey text field at site information and set the site key.
 - Checks if siteapikey is set if its set the Change submit button name from Get 
   Configuration to Update Configuration
 - It will create 'page' content display in json format with endpoint url
   page-json/key/{nodeid} where {nodeid} will replace the node id of a page content type
   if id matches it will return title of that node in json format if not it will return
   error access denied. It will also check if siteapikey is set or not.  