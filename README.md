# COHT

# Description
I made the decision to develop an Android app that would recognise an automobile accident and notify both the user's primary contacts and first responders. The app's main goal was to increase security for consumers and their families.
# Screenshot
Here are a few screenshots of the final App

<img src="screen shot/WhatsApp Image 2023-07-02 at 2.19.50 PM.jpeg" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="200" height="400" />

<img src="screen shot/registerpage.jpeg" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="200" height="400" />

<img src="screen shot/dashboard.jpeg" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="200" height="400" />

<img src="screen shot/emergencycantact.jpeg" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="200" height="400" />

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
