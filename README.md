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

It consists of background image, title, and refresh link. Refresh link is the “UFO Sightings” text. When user click the text, it will automatically reset the filters and show all the data in the table. Figure 2 will show us more detailed about the header.

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/140633235-3d5dddbf-5c14-478a-bddc-71b125aa9083.png"/>
  </p>
  
<p align="center">  
  <sub> Figure 2 Header</sub>
</p>

* Article

The article is under the header and consists of 2 columns which are the title of article and the article itself. 

* Filters and Table

When the page is displayed for the first time or when user click the refresh link, all the data in the table will be shown. The data in the table can be filtered with multiple criteria at the same time when there are change in the filters. Figure 3 shows all the filters that can be used to filter the data. It is a text field which user can type with suggested text and format of how search criteria should be entered. For example, in Date it suggests 1/10/2010 format with forward slashes and without extra 0 before day and month. City, state, country and shape must use lowercase.

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/140633290-19d59fbc-fc15-432d-88dc-666f45fee30e.png"/>
  </p>
  
<p align="center">  
  <sub> Figure 3 Filters</sub>
</p>

After user input the criteria, the table will automatically display only rows that matches the user input. Figure 4 show us the example of the data change when user enter 1/4/2010 as date and ca as state.

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/140633313-1cfd58c2-aa4f-4c95-837d-6b5e474caa4c.png"/>
  </p>
  
<p align="center">  
  <sub> Figure 4 Change in Table after Filters</sub>
</p>


## 4 Summary

Some drawback and recommendations for further development:

Drawback:
* All the data in the table is displayed when user load the web at the first time or click the refresh button. The page become too long, and it can be taken time to load, especially if the data will be larger. 
* The filters search are not flexible with the format.  For example in city , state , country or shape , user must input it in lowercase ,if it’s not in lowercase the data won’t be displayed
* The refresh page link is too far away and not noticeable. 

Recommendations for further development:
* The table will display only the top 10 latest UFO sightings. By displaying only the top 10 , the page will be more compact and it will need shorter time to load. To make sure the user know that there are more information that can be displayed, there will be information in top of table that the table only display the latest 10 UFO sighting and user can search by using filters to display more information they want.
* To navigate more easily we can put Date From and Date To using date picker, so user can search in the time range and easily pick the data without worrying the format using the date picker.
* Dropdown for City, State, Country and Shape. By using dropdown user can easily pick the choice of input that’s already in database and they don’t need to worry about the format they should input  
* Put the refresh page link under the search criteria so the user can easily click the link to reset filters.


