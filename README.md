# Tower Collector
Join the OpenCellID community and collect cell towers' locations from your area!

The app is designed to help map the extent of mobile phone network coverage of GSM/UMTS/LTE/CDMA cell towers using GPS locations. This is accomplished by reading GPS coordinates and identifiers of mobile network transmitters in regular intervals. Collected information is saved on your phone's storage and can be uploaded directly to the [OpenCellID](http://opencellid.org) database. It is also possible to collect measurements for private purposes and export them to CSV or GPX files.


## Building
This project is build using Android Studio 2.1.

To build your own signed apk go to "[app/properties](app/properties)" and:

 1. Place your keystore file inside the folder.
 2. Copy "[example.properties](app/properties/example.properties)" as "private.properties" in the same directory and adjust it accordingly.
 3. Copy "[google-services-example.json](app/google-services-example.json)" as "google-services.json" in the same directory and adjust it accordingly or place your own generated file there.
 4. These files will be ignored so don't worry about committing them by mistake.

## Bug reports and feature requests
Please report any bugs or submit feature requests through the *Issues* tab on this page or email me directly.

## Translations
If you would like to help out with translation, please visit http://i18n.zamojski.info/

## License
TowerCollector is licensed under the Mozilla Public License 2.0.  A copy of this license is included in [LICENSE.txt](LICENSE.txt).
