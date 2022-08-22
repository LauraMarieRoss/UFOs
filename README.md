# UFOs
## Project Overview
The objective of this project is to build and deploy a webpage using HTML, CSS, JavaScript. JavaScript functions are used to create, populate, and dynamically filter a table on the page.
<br><br>
The data used is a JavaScript object containing UFO sighting information, such as the date, city, state, country, and visual category of the UFO witnessed. The visual components of the website were created using Bootstrap, a popular CSS framework allowing for flexible and dynamic website customization.

## Resources

<b>Data Sources:</b><br>
- data.js, a JavaScript object supplied as a learning tool for the exercise<br>

<b>Components:</b><br>
- JavaScript for parsing the data and creating functions to display and filter the data.<br>
- Bootstrap (https://getbootstrap.com/) for HTML and CSS website components<br>
- IntelliJ IDEA 2022.2 coding environment<br>

## Results
The final webpage can be found <a href="https://github.com/LauraMarieRoss/Movies_ETL/blob/main/ETL_function_test.ipynb" target="_blank">here.</b></a><br>

Filtering the data can be done by using the table on the left side of the page (seen here):



Simply enter one or multiple search criteria, such as the date of the sighting, the city, State, Country, and/or Shape of the UFO sighted into the corresponding search box. Click "Filter Table" to filter for the entered search criteria. <br>
<br>
In this example the table has been filtered for "ca" in the "State" search box.

To clear the filter, clear the search criteria and click "Filter Table", or reload the page.

## Summary
There are a few drawbacks to the current design:
- It is not clear to the user where the data was gathered from.
- There is no menu showing the sighting "Shape" options or defining what is meant by "Shape".
- The possible date range is not clear.
- Country and State abbreviations may not be obvious to the user.
- All input is case-sensitive.
<br><br>

Suggestions for further development:
- Include information about the data source (in this case it was supplied as part of a student exercise, but for deployment clear data sources should always be supplied).
- Supply possible date ranges and include a calendar pop-up to guide the user.
- Remove case-sensitivity.
- Display menu options for City, State, Country, and Shape.
- Describe and refine what is meant by UFO "Shape".
