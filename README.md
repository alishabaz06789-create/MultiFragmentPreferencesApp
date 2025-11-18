📱 Multi Fragment App with SharedPreferences

This project is a simple Android application made for my assignment. It has two fragments and uses SharedPreferences to save and show user data. The main purpose of this app is to store user preferences and make them available even after the app is closed.

-> What the App Does

Fragment 1 lets the user enter:

Username

Email

Password

Theme color (Light / Dark / Blue)

Notification setting (On/Off)

The data is saved using SharedPreferences.

Fragment 2 shows the saved data every time the app is opened.

The theme color also changes the background so the UI looks different.

-> Features

Simple UI with two fragments

Data validation before saving

Preferences stay saved even after app restart

Easy navigation between fragments

Reset button to clear all saved data

-> How I Built It

I created two fragments using Java + XML.

Used SharedPreferences with getSharedPreferences() to save and load user data.

Used FragmentManager to switch between fragments.

For theme color, I changed layout background based on saved preference.

Added a Reset button to remove all saved settings using .clear().

-> What I Learned

How to use SharedPreferences for persistent storage

How fragments communicate in Android

How to update UI based on stored values

How to manage navigation between fragments

===> How to Run

Download or clone the project

Open it in Android Studio

Run it on an emulator or real device

Enter data in Fragment 1 → Save

Go to Fragment 2 to see stored data
