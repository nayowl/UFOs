# UFOs
## 1 Overview
The UFO Project is a dynamic webpage that display data about UFO sighting. The data is displayed in table and can be filtered with multiple criteria like date, city, state, country and shape at the same time. The following task will be performed in this project:
* Use HTML to build the webpage and use CSS and bootstrap to style the webpage
* Display data in the dynamic table that can be filtered with multiple criteria like dates, city, state, country and shape at the same time.

## 2 Resources
Data source: data.js, nasa.jpg

Software : HTML, CSS, Bootstrap, JavaScript

## 3 Results

 <p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/140633184-b36c6cad-48b9-4511-8184-3df30e6051e2.png"/>
  </p>
  
<p align="center">  
  <sub> Figure 1 Webpage of UFO sighting </sub>
</p>

Figure 1 shows us the whole web page when user click the website. It divided into 3 segments:
* Header

It consists of background image, title, and refresh link. Refresh link is the “UFO Sightings” text. When user click the text, it will automatically reset the filters and show all the data in the table. Figure 2  presents the header in more detail.

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/140633235-3d5dddbf-5c14-478a-bddc-71b125aa9083.png"/>
  </p>
  
<p align="center">  
  <sub> Figure 2 Header</sub>
</p>

* Article

The article is under the header and consists of 2 columns which are the title of article and the article itself. 

* Filters and Table

All the data in the table will be shown when the page is displayed for the first time or when the user clicks the refresh link, . The data in the table can be filtered with multiple criteria at the same time when there are changes in the filters. Figure 3 shows all the filters that can be used to filter the data. It is a text field where user can type suggested text and format of how search criteria should be entered. For example, in Date it suggests 1/10/2010 format with forward slashes and without extra 0 before day and month. City, state, country and shape must be in lowercase.

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/140633290-19d59fbc-fc15-432d-88dc-666f45fee30e.png"/>
  </p>
  
<p align="center">  
  <sub> Figure 3 Filters</sub>
</p>

After the user input the criteria, the table will automatically display only rows which match the user input. Figure 4 shows us the example of the data change when user enter 1/4/2010 as date and ca as state.

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/140633313-1cfd58c2-aa4f-4c95-837d-6b5e474caa4c.png"/>
  </p>
  
<p align="center">  
  <sub> Figure 4 Change in Table after Filters</sub>
</p>


## 4 Summary

Some drawback and recommendations for further development:

Drawback:
* All the data in the table is displayed when the user loads the web at the first time or clicks the refresh button. The page becomes too long, and it could takes to load, especially if the data gets larger. 
* The filters search are not flexible with the format of the input.  For example in city , state , country or shape , user must input it in lowercase ,otherwise  the data will not be displayed
* The refresh page link is located way too far and might not noticeable by the user. 

Recommendations for further development:
* The table will display only the top 10 latest UFO sightings. By displaying only the top 10 , the page will be more compact and take shorter time to load. To make sure the user knows that there is more information that can be displayed, there will be information on top of table that the table only display the latest 10 UFO sightings and user can conduct searches by using filters to display more information they want.
* For easier navigation "Date From" and "Date To" can be added using date picker format, the user can search in the time range and easily pick the data without concern about format.
* Adding dropdown for City, State, Country and Shape. By using this feature user can easily pick the choice of input that’s available in database and they don’t need to worry about the format they should input  
* Put the refresh page link under the search criteria for enable the user to easily click the reset filters link.


