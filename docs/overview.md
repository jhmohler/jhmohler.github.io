# My Favorite Albums

My Favorite Albums is data analysis software for music that allows a user to compile and analyze their own music rankings and listening activity, or view and analyze the rankings of others. This overview will cover two separate use cases: 
- Using My Favorite Albums to view and analyze the album rankings of someone who has made a My Favorite Albums page 
- Using My Favorite Albums to create a page to view and analyze your own album rankings.

### Analyzing Someone’s Music Rankings With My Favorite Albums

After you navigate to a My Favorite Albums page in any browser, you can use the various different tabs on the page to analyze the owner’s music rankings. There are five different tabs that each provide a different function for you to use:

**Number One Albums**  
This tab allows you to view the page owner’s favorite albums within a specific range of years. After choosing a range, the table below will update and show each year along with the page owner’s top rated album from that year and the album’s artist.

**Bands and Artists**  
This tab allows you to choose an artist or band and view the page owner’s rankings for that artist’s music. After selecting an artist, a table will appear below that displays each of the artist’s albums with their release year and rating. It will also display the number of the artist’s albums ranked by the page owner and the average album rating of that artist.

**Top Albums by Year**  
This tab allows you to choose a year and view the page owner’s ranking of all albums released that year. After choosing a year, each rated album that released that year will display in the list below along with their ranking and artist.

**Vinyl**  
This tab displays information about vinyl the page owner owns. It shows both the page owner’s top rated albums that they do not own vinyl for, as well as a list of each year and how many vinyl records released in that year the page owner has. Only unowned vinyl with a rating of at least 9 will be displayed in the top rated albums.

**Band Comparison**  
This tab allows you to select two different bands or artists, and then compare album ratings between the two. After you select the two, the line chart below will update to show both bands' or artists' albums by ranking and year released.  

### Creating a My Favorite Albums Page
To analyze and view your own album rankings using My Favorite Albums, you will need to create your own My Favorite Albums page. To start creating your page, you will need to download My Favorite Album’s software from its [GitHub page](https://github.com/UW-Example-Student/MyFavoriteAlbums/tree/main). Once the software is downloaded, this process will require you to have R and RStudio installed, as well as access to a .csv file editor. However, no prior experience in R or any other programming language is required.

**Album Rankings Data**  
To create a My Favorite Albums page, you must first create the file storing your album rankings and information. My Favorite Albums uses the .csv file format to do this, which can be edited in a spreadsheet software such as Microsoft Excel or Google Sheets. My Favorite Albums will search for data within a .csv file named ‘album-rankings.csv’ within its ‘data’ folder. If you fill a .csv file named this with your album rankings in proper format and place it into the ‘data’ folder, My Favorite Albums will pull these rankings from the file and allow you to analyze them once you finish creating the page. The ‘Number One Albums’ and ‘Band Comparison’ features of My Favorite Albums only support albums released between the years 1993 and 2024, as well as album ratings between 0 and 10\.

**App Startup**  
After being provided the data, all that My Favorite Albums needs to do to create a page is to run ‘app.R’. Running a My Favorite Albums page without editing its code will cause the page to be hosted locally, meaning that it can only be viewed from the same device you are running the page on. When ‘app.R’ is run in RStudio, it will automatically create a pop-up window of your My Favorite Albums Page, allowing for you to immediately start using it.

