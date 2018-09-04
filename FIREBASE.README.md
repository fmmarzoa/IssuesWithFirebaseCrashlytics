# Firebase Crashlytics Integration

The original app for this example has been taken from here:

https://codelabs.developers.google.com/codelabs/android-instant-apps/#0

Integrated Firebase Crashlytics following this official document:

https://firebase.google.com/docs/crashlytics/get-started

I got into some support library conflicts right after adding com.google.gms.google-services. I managed to work those around.

Now, if I try to build the APKs I get the following error, as expected:

"No matching client found for package name 'com.google.samples.apps.topeka.base'"

I'm going to add some branches with workarounds I have tried.


