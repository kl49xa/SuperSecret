# SuperSecret
Android Application

Open your Android project in Android Studio.

Select Tools > Firebase to open the Assistant window.

Expand one of the listed Firebase products (for example, Analytics), then click the provided tutorial link (for example, Log an Analytics event).

Click Connect to Firebase to register your app with an existing or new Firebase project and to automatically add the necessary files and code to your Android project.

Check that your plugin and library versions are up-to-date:

In your root-level (project-level) Gradle file (build.gradle), check that your Google Services plugin version is up-to-date (com.google.gms:google-services:4.3.3).

In your module (app-level) Gradle file (usually app/build.gradle), check that your Firebase Android library versions are up-to-date.

Note: If you're using Android Studio v3.2 or earlier, also make sure that each dependency line only has one version number specified.
Sync your app to ensure that all dependencies have the necessary versions.

Configure your Analytics data sharing settings in the Firebase console Project settings.
Enabling the sharing of Analytics data with other Firebase products is required to use Firebase products like Firebase Predictions or Firebase A/B Testing.

Run your app to send verification to Firebase that you've successfully integrated Firebase.

Your device logs will display the Firebase verification that initialization is complete. If you ran your app on an emulator that has network access, the Firebase console notifies you that your app connection is complete.
