# Pothole-Finder-and-Augmentation-Navigation
This application detects the potholes and displays the location of potholes on map and allows the user to remove fake potholes.

Varun:
Login authentication and sign up.
UI development and enhancement.
SQliteHelper class , Login activity class , register activity class, Pothole class displaying the list of potholes existing in the database.
and fill pothole class which removes the pothole from the database.

Ramyashri:
MainActivity: This acticvity class extracts the accelerometer sensor data that is present in the mobile using onSensorChange() event. This function is called when the values of the sensor changes.A threshold value is set, value greater than which is detected as a 'Pothole'.User can include pothole at current location.
DBHandler: Pothole database was implemented using SQLite and managed using a database handler class with location table consisting of the Pothole ID, Latitude, Longitude and Frequency.Frequency is the number of times the pothole is detected in same location.

Saurabh Hegde:
MapActivity: My contribution  is mainly towards the maps acivity , that is creating Restricted maps api and creating oncreate and onmapready functions.
creating action listeners for markers and maps touch.
Some of the fuctions in dbhandler that is to pullout the data from the database and loop it over the marker function.
addlocation functio to check whether new value has to be updated at existing coordinates or insert new coordinates.

Finally helped a little on UI of fillpothole function whereever maps activity is concerned



