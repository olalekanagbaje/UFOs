# UFOs

## **Overview of the Project**

The purpose of this project is to build a dynamic UFO sightings webpage that can accept multiple input / filtering parameters (such as date, city, state, country & shape) from users and display some visually insightful dynamic tabular data about UFO sightings in some states of the USA.  

In order to provide these visually insightful data, my webapge / analysis was tailored to;

  1. Filter UFO sightings on multiple criteria
  2. Create a written report on the UFO analysis
  3. Create a written report for the statistical analysis

To generate this analysis, I utilized the following resources;

  - Data Source: data.js
  - Softwares: Javascript, HTML, CSS, Bootstrap



## **Result**
  
The steps enumerated below describe how a user can use the dynamic UFO sighting webpage to extract insightful data using the search parameters on the webpage;

- Step 1: Copy the relative path of the index.html (file:///C:/Users/Administrator/UFOs/index.html) into a web-browser and click on Enter to launch the homepage of the webpage. By default the homepage is designed to load and display the a number of UFO sightings data. The 2 images below show the homepage.



- Step 2: Navigate to the "Filter Search" section of the homepage, which houses the search criteria input fileds- Enter a Date, Enter a City, Enter a State, Enter a Country & Enter a Shape. Users can then input one or more appropriate filter parameters / criteria of their choice using the format of the placeholder in the input fields and press enter on their keyboard to fetch the filtered data. 



The 2 images below show the results of filter searches using combination of Date = 1/1/2010 & Shape = Triangle ; While the 2nd is a combination of Date - 1/1/2010 & Shape = Unknown.



 - Step 3: Inputed data can be cleared from the search fields by using the backspace button on the keyboard.



 ## **Summary**

In summary, the points below highlight one major drawback of the current webpage design and two recommendations to improve the page;


**Drawback:** 

 _- The input fields of the "Filter Search Section" of the current webpage is case sensitive / format sensitive. If for example a user enters a search parameter such as "circle" in capital letters in the "Enter a Shape" field, no UFO data will be returned by the webpage despite the fact such data for circle shape are present in the data table. In thesame manner, if input data for "Date field" isn't enter in the date format shown in the Date placeholder, no UFO data will be returned even if data for such date is present in the data table._

**Recommendation for Further Development:**

_To further optimize the webpage for better user experience, the following recommendation could be considered;_

 _- In place of using a search input field that allows users to type /enter their input criteria directly from theor keyboard, the search fields could be redesigned to have drop-down menu options for each search field. The drop-down menu will have pre-defined data options / patterns that the user can select from. For example, the "Shape" field could have pre-defined drop-down menu options like circle, tirangle, unknown, fireball etc for the user to select. In a similar manner, the date field could be redesigned to have a calender option that is activated once a user clicks on the date field, which enforces the user to select his prefered date from the calender. These suggestions could help reduce / eliminate input errors in the search fields_  

 _- The webpage could also be redesigned to accomodate a download (export) option for the filtered UFO sightings data to common file formats such "csv", "xls", "txt" etc. This could enhance the experience of certain users that may need to re-use such filtered data for other purposes outside the webpage._

