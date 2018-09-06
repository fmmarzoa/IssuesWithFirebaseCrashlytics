# Firebase Crashlytics Integration

I have updated the gradle wrapper to version 4.10 and the com.android.tools.build:gradle to version 3.3.0-alpha08
as suggested by a comment in my StackOverflow question:

https://stackoverflow.com/questions/52099797/conflicts-with-google-instant-game-and-com-google-gms-google-services-plugin

Now the code at least builds without major problems. There is a warning saying that I should put the google services
plugin at the bottom of the file in the instant module, but it turns out that it is already at the bottom of such file,
so I'll ignore that.

I'm going to add firebase crashlytics to the project now, following this official guide:

https://firebase.google.com/docs/crashlytics/get-started

After adding crashlytics I get the following error while building:

_Crashlytics could not find the manifest. 
Not found at /Users/fran/Desktop/Idea/android-topeka/base/build/intermediates/merged_manifests/debug/AndroidManifest.xml_

