Assessment 2 Login Api App
logs into an api and display entites given by a keypass onto a dashboard screen

Description
This app allows you to login to an api using a your student login it will then move you to a dashboard screen where it will display a list of entities based off of the keypass given to you by the dashboard. 
This app also has click functionality which will take you to a details screen when a entity is clicked on.

Getting Started
To run this app you mnust first add the dependencies needed:
implementation(libs.retrofit)
implementation(libs.converter.gson)
implementation("com.squareup.retrofit2:retrofit:2.11.0")
implementation("com.squareup.retrofit2:converter-moshi:2.11.0")
implementation("com.squareup.moshi:moshi-kotlin:1.14.0")
implementation("com.squareup.okhttp3:logging-interceptor:4.10.0")

Make sure android studio is on the latest version to run the app

Installing
To use and install this app: 
* clone the app to your android studio
* Wait for it to load and build
* Install any dependencies
  
How to run the program
To run this program:
* Select the run button in android studio once ready
* After running type in the username Christian
* Then type in the password s4659183
* This will connect to the api

Authors
Christian Marino

Acknowledgments
https://square.github.io/retrofit/
https://www.youtube.com/watch?v=HagZBlNevLQ&ab_channel=AndroidKnowledge
