# Singapore Azure Bootcamp

This is the GitHub repository for Azure Bootcamp - Singapore Chapter. 
The live version of 2015 bootcamp website (hosted as Azure Website) is available at 
- Main website: **[Singapore Azure Bootcamp](http://singapore.azurebootcamp.com)**
- Routed website: **[Singapore Azure Bootcamp](http://globalazurebootcampsg.azurewebsites.net)**

Feel free to **fork** it and use it, but do remember to update the Speaker and Sponsors photographs


## Technology Stack

- HTML5
- jQuery
- CSS3
- **[Stackhive](http://www.stackhive.com)**

## How to use it?

- Fork the master branch
- Clone on desktop
- Upload to [Stackhive](http://www.stackhive.com) 
- Start editing html/js/css files

## Wishlist

- Read the list of speakers (and their profile pic) and agenda from JSON file

## Continous Deployment to Azure WebApp

- When setting up the GitHub URL, please make sure you are using the Forked version
- After the deployment has succeeded, you will get HTTP 404 or HTTP 403 error
- To fix that, in the WebApp > Configure tab, make sure that the virtual path settings look like
  /              site\wwwroot\2015\src
- Once changed, save the settings and refresh the website

