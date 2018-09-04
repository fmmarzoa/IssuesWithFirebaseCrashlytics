# Firebase Crashlytics Integration

In this workaround branch I just replaced the app name of the base module in its AndroidManifest.xml file with the one 
of the app itself, so firebase finds the right id. As a result, I will have to replace also all the R class imports to
use the app package id instead of the base package id.

But as expected, by doing this I get a new conflicting error when Trying to build the app:

Program type already present: com.google.samples.apps.topeka.BuildConfig
Message{kind=ERROR, text=Program type already present: com.google.samples.apps.topeka.BuildConfig, sources=[Unknown source file], tool name=Optional.of(D8)}

So this workaround seems to be a dead end.
