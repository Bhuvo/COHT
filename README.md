# COHT

# Description
I made the decision to develop an Android app that would recognise an automobile accident and notify both the user's primary contacts and first responders. The app's main goal was to increase security for consumers and their families.
# Screenshot
Here are a few screenshots of the final App

<img src="https://github.com/Bhuvo/COHT/assets/138361584/ab160200-6121-4ffa-b854-7e002b7dc6c1" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="200" height="400" />

<img src="https://github.com/Bhuvo/COHT/assets/138361584/0d97e320-1c05-4c53-affd-998b906a59d1" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="200" height="400" />

<img src="https://github.com/Bhuvo/COHT/assets/138361584/2bb73d21-14d4-425b-8d05-ec84beedf2bd" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="200" height="400" />

<img src="https://github.com/Bhuvo/COHT/assets/138361584/4b74dcf7-653b-4a80-9edd-23eeee194fa8" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="200" height="400" />

# Technology Used
<h3>Android Studio</h3>

I used Android Studio to develop the app.

<h3>Firebase</h3>

I used Google Firebase to help us conduct user authentication and maintain a backend database for our application. I used the following videos and resources to understand how to incorporate Firebase into our app.

<h4>Add the following dependency to the app-level build.gradle file:</h4>

  compile 'com.google.firebase:firebase-auth:9.6.1'
  
  compile 'com.google.firebase:firebase-database:9.6.1'

<h3>Google API</h3>

Collected the user's coordinates using the Google Maps API, which we then utilised to track the user's location and speed.  At faster speeds, this app's accident detection feature was triggered. Additionally, we used this api to look up the addresses and phone numbers of the closest hospitals.
