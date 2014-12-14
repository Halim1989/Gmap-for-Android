Gmap-for-Android
================

Displaying the google map in Android

Open the Project in the Android developer tool

Create an Android Key :
go to https://console.developers.google.com/project -> Create a new projet or use an existing one.
On the lef side bar, go to Identier -> Create a key -> Android key -> past the SHA1 fingerprint and the pacakge name of the project separated with semicolon.

To find the SHA1 fingerprint of your application :
Go to Android developer tool and click on windows -> preference -> Android -> Build -> SHA1 fingerprint

After creation, a key is generated. Copy it, we will need it in our project.

open the AndroidManifest of the GmapExample project.

Search for this lines of code 
test
<meta-data android:name="com.google.android.maps.v2.API_KEY" android:value="Put here the generated android key" />
