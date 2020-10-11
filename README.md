# google map api (in) filemaker (forstef)
A filemaker app that integrates google map api for drawing regions and testing coordinates.

------------HOW TO USE---------------------

draw your polygons and remember to name them. You can also edit the name of your areas in the "region" layout

 Enter your coordinates into the longitude and latitude fields in the region layout. Remember to use the "New Record" button.
 
 You can also check and edit your coordinates from the dataLocation layout. You can as well import your coordinate into those fields, as you wish...
 
 When your polygons and coordinate data are ready. Click the Start button IN THE REGION LAYOUT(Note: there are two start buttons. Use the one in "region" layout to send your data to the webviewer...
 
 Then finally move to the "stef" layout. This is where your map is. Click the start button here to compute areas. Areas will be computed for each coordinate and the result will be stored in the dataLocation layout table in JSON format, because a coordinate has many to many relationship with your areas or polygon...
 
 Note: Your coordinates data will be used to create markers for visual feedback so you can easily locate them and where they belong on the map.
 
 You can also change the api key from the stef/map layout...
 
 You can also export your data to an external json file by running the appropriate scripts...from the script workspace.
