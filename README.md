# Easify

A home-services booking app for Android. Customers browse services, see the minimum service charge, and book an appointment at their location. They pay only once they're satisfied with the service. Built in 2023 as a college project.

This is the **customer app**. Service partners use a separate app to accept requests: [Easify Service Partner](https://github.com/aswinakofficial/Easify-Service-Partner-App).

## Features

- **Browse and book**: see the available services and their minimum charge, then book with your address and landmark
- **Location**: pick your location with Google Places search
- **Manage orders**: view and cancel your appointments
- **Accounts**: sign up or log in with email or Google, reset your password, and a profile page

## Stack

Java on Android, Firebase Authentication and Realtime Database, Google Places API.

## Run it

1. Open the project in Android Studio.
2. Create your own Firebase project with Authentication and Realtime Database. Replace `app/google-services.json` with yours, and set up database rules so each user can only read and write their own data.
3. Add your own Google Maps/Places API key in `AndroidManifest.xml`.
4. Build and run on an emulator or device.

---

Part of [Aswin AK's projects](https://aswin.xpar.in/projects/).
