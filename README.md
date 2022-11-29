Ultimate weather app
---------------------

Experimental app to consume Weather API


## Baseline App

The basic structure of the App is as follows

![structure](assets/structure.png)

There are 2 "heads" one for Android and one for iOS. These are the Applications that actually get compiled and run on the devices.

They are Xamarin.iOS and Xamarin.Android Applications, without any frameworks installed.

The project structure is a layered structure:

- Domain contains entities and interfaces
- Data contains the data layer that fetches data from APIs
- Presentation layer consumes Domain and Data layer to prepare and present data to the user

The heads consume all of these projects.

### iOS
![iOS screenshot](assets/ios.png)

### Android
![Android screenshot](assets/droid.png)

### Data
Data : https://https://api.weatherapi.com/v1/

