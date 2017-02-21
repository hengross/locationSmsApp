# locationSmsApp

This project is an Android app that allows user to identify the location or of "his friends" using the following interfaces:
1 .mmsk location: based on a combination of fibrous GPS location, and radio (WiFi, 4G, 3G.)
2 .mmsk BLE: service enabling signal sensing Bluetooth Low Energy-purpose revaluation location.
3 .mmsk QR, allowing the camera to detect the use of "barcodes".
The database is updated from the remote server. We used in the database FireBase google it updated the objects:
1. Users
2. Position each user, that would be brought there and at this point it is
3. BLE components scanned by app

1 The user can see their location on a map as calculated by the system (GPS and radio signals).
2 The user will be able to see the position and speed of its phone Web site, the location is updated every 10 seconds in the case of OnLocationChange.
3 The user can "link" between its current location and information: Whether it is scanning BLE and if it's contagious, "bar code".
4 The user will be able to identify their location with a search for "barcode" or BLE ID-Tag
