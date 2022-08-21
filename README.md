# UFOs
## Overview of the analysis:
The purpose of this analysis was to create a web app to display data on UFO sightings. The web app includes an article about UFOs followed by a table that contains data on potential UFO sigthings. The table also includes filters, which allow the user to filter the table based on date, city, state, country, and shape. The data found in the web app is stored in a JavaScript document and the tables filter uses JavaScript and the d3 library.
## Results:
![webapp](https://user-images.githubusercontent.com/107213807/185769640-43fe3028-74f2-45ed-9c34-27a8c0955242.png)

Let's say someone wanted to find out if there are any UFO sightings in there local area. For this example, this individual lives in El Cajon, CA. First they would go the the filter form to the left of the table.

![filter_form](https://user-images.githubusercontent.com/107213807/185769711-d181ad85-ad53-40aa-a62a-82d54bb0e2c2.png)

After finding the city field, they would type in el cajon.

![city_filter](https://user-images.githubusercontent.com/107213807/185769725-e88e38e1-923c-4223-a87d-b2d54577eb3e.png)

When the individual hits enter, the table becomes filtered only showing sightings where the city is El Cajon.

![city_filtered_table](https://user-images.githubusercontent.com/107213807/185769751-8f05a8f2-bd89-4cd4-9cc4-6587ee35df41.png)

The good thing about this filter is that it allow's the user to filter the table using more than one field. For example, let's say the individual heard about a triangle in the sky in El Cajon and wanted to investigate. 

![city_shape_filter](https://user-images.githubusercontent.com/107213807/185769841-a841c996-c4b8-44ca-b920-e95a61ccaa76.png)

After the user fills in the correct fields, the table becomes even more filtered.

![city_shape_filtered_table](https://user-images.githubusercontent.com/107213807/185769853-e33c0cb1-902d-42af-9268-920e2e9626e8.png)

As seen above, the web app is pretty simple to use. The code that makes it work however is not quite as simple.



## Summary:
