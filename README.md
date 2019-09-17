# MetCollection
A visualisation of the origins of the MET Gallery collection created using P5.js.
Based on the following example for Mappa.js - https://mappa.js.org/docs/animated-meteorite-landings.html


The following dataset was used - https://github.com/metmuseum/openaccess/blob/master/MetObjects.csv
This dataset was cleaned using Python and due to missing information, dating ambiguity, or to the presence of antiquated names for countries, only half of the dataset was usable. Nevertheless, the visualisation documents the origins of about 200,000 items in the museum.


The visualisation itself charts the age of the individual objects within the collection rather than the year they were acquired by the gallery. Where the dating of an object lay between a range of years, the average value of that range was used. The movement of artifacts is denoted by red circles which travel across the map from the country of origin to the gallery in New York. The size of the circle represents the number of objects in the gallery dated to that particular year.


## Link to visualisation and P5.js code
https://www.openprocessing.org/sketch/695430
