# UFOs
## Project Overview
The objective of this project is to build and deploy a webpage using HTML, CSS, JavaScript. JavaScript functions are used to create, populate, and dynamically filter a table on the page.
<br><br>
The data used is a JavaScript object containing UFO sighting information, such as the date, city, state, country, and visual category of the UFO witnessed. The visual components of the website were created using Bootstrap, a popular CSS framework allowing for flexible and dynamic website customization.

## Resources

<b>Data Sources:</b><br>
- <a href="https://github.com/LauraMarieRoss/UFOs/blob/main/static/js/data.js">data.js</a>, a JavaScript object supplied as a learning tool for the exercise<br>

<b>Components:</b><br>
- JavaScript for parsing the data and creating functions to display and filter the data.<br>
- Bootstrap (https://getbootstrap.com/) for HTML and CSS website components<br>
- IntelliJ IDEA 2022.2 coding environment<br>

## Results
### Final Page
The final webpage can be found <a href="https://lauramarieross.github.io/UFOs/" target="_blank">here.</a><br><br>
<a href="https://lauramarieross.github.io/UFOs/">
         <img alt="UFO Webiste" src="https://user-images.githubusercontent.com/105830645/185825358-f4cb89ba-8e33-408e-86d4-02ac605df7e1.png"></a>

### Filtering
Filtering the data can be done by using the table on the left side of the page (seen here):<br>
<img src="https://user-images.githubusercontent.com/105830645/185825825-9518e1ae-cde0-4344-8596-3f051617f1f9.png" width = "350">


<br>
Simply enter one or multiple search criteria, such as the date of the sighting, the city, State, Country, and/or Shape of the UFO sighted into the corresponding search box. Click "Filter Table" to filter for the entered search criteria. <br>
<h4> Filtering Example </h4>
In this example the table has been filtered for "ca" in the "State" search box.<br>
<img src="https://user-images.githubusercontent.com/105830645/185826150-839ac98d-d9e6-4a57-a171-2506ae154ae0.png">


To clear the filter, delete the search criteria where it was entered and click "Filter Table", or reload the page.

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
