# Firebase Crashlytics Integration

In this workaround I'm going to keep the package ids as they are and instead I'll set the google_app_id manually in the 
res/values/strings.xml file.

Unfortunately this continues complaining about:

"No matching client found for package name 'com.google.samples.apps.topeka.base'"

In my production app, nonetheless, this seems to give a different problem but it didn't worked anyway.
