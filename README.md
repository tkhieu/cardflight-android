CardFlight's Andriod SDK Library
=================


Introduction
------------

CardFlight's API is based around keeping it as simple as possible, however keeping the highest level of [security](http://#) at the forefront of all that we do. Taking out the pain of PCI-compliance when building your app.

Authenticationis done thorugh your API Keys and processing is done through the Account Tokens. All connections to CardFlight's API id done thorugh HTTPS over HSTS.

[JSON](http://www.json.org) is used where possible upon returning responses from the API, including errors.



Setup
----------

Add CardFlight.jar library in the libs folder of the project of your application. Once the jar has been added, add the required permissions in the AndroidManifest.xml file.

##### Example

```
<uses-permission android:name="android.permission.RECORD_AUDIO" />
<uses-permission android:name="android.permission.MOUNT_UNMOUNT_FILESYSTEMS" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.INTERNET" />
```

You will also need to set the CardFlight activity for the ManualEntryActivity class.

```
<activity android:name="com.cardflight.ManualEntryActivity">
```

SDK Documentation
--------------

Click on the topics below to learn more about our SDK.

| Topics |
| ------------ |
| [Errors](https://developers.getcardflight.com/docs/api/android#errors) |
| [Initialization](https://developers.getcardflight.com/docs/api/android#initialization)|
| [Swipe Card](https://developers.getcardflight.com/docs/api/android#swipe_card)|
| [Swipe Response](https://developers.getcardflight.com/docs/api/android#swipe_card_response)|
| [Keyed Entry](https://developers.getcardflight.com/docs/api/android#keyed_entry)|
| [Keyed Response](https://developers.getcardflight.com/docs/api/android#keyed_response)|
| [Process Payment](https://developers.getcardflight.com/docs/api/android#process_payment)|


Supported Platforms
-----------------------

Our SDK supports a wide array of Android platforms. [Click here](https://developers.getcardflight.com/docs/android) to view an updated list.


Looking for iOS?
-----------------

We've got you covered. [Click here](https://github.com/CardFlight/cardflight-ios) to learn more about our iOS SDK.


Questions?
--------

CardFlight is currently in private beta. If you would like to get a hold of our private beta, register here at https://getcardflight.com or email at devs@getcardflight.com. In the meantime, please watch this repo as well will be pushing our first version very soon.
