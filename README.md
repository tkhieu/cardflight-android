CardFlight's Android SDK Library
=================

Introduction
------------

The CardFlight iOS SDK is used to process card present and card not-present transactions in your Android application.

CardFlight's SDK is based around keeping it as simple as possible while keeping the highest level of [security](https://developers.getcardflight.com/help/security) at the forefront of all that we do. Take out the pain of PCI-compliance when building your app.

Authentication is done through your API Keys and processing is done through the Account Tokens. All connections to CardFlight's API are done through HTTPS over HSTS.


Setup
----------

Add **cardflight.jar** library in the libs folder of the project of your application. Once the jar has been added, add the required permissions in the AndroidManifest.xml file.

### Installation

```
<uses-permission android:name="android.permission.RECORD_AUDIO" />
<uses-permission android:name="android.permission.MOUNT_UNMOUNT_FILESYSTEMS" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.INTERNET" />
```

### Initialize

To access your CardFlight account you will need to set your Developer API key and the associated Merchant Account Token that you wish to connect to when making payments.

##### Example

```
CardFlight.getInstance().setApiTokenAndAccountToken("e9cb15260f08e738b782952895d4ba4f", "acc_04ff8bf650afb268");
```

The CardFlight SDK is broken into easy-to-manage components. You just include the ones that you want to use in the header files of the classes that need to access those components.

SDK Documentation
--------------

- [Errors](https://developers.getcardflight.com/docs/api/android#errors)
- [Reader Initialization](https://developers.getcardflight.com/docs/api/android#reader_initialization)
- [Swipe Card](https://developers.getcardflight.com/docs/api/android#swipe_card)
- [Swipe Response](https://developers.getcardflight.com/docs/api/android#swipe_card_response)
- [Keyed Entry](https://developers.getcardflight.com/docs/api/android#keyed_entry)
- [Keyed Response](https://developers.getcardflight.com/docs/api/android#keyed_response)
- [Charge Card](https://developers.getcardflight.com/docs/api/android#process_payment)
- [Refund Charge](https://developers.getcardflight.com/docs/api/android#refund_charge)


Supported Platforms
-----------------------

Our SDK supports a wide array of Android platforms. [Click here](https://developers.getcardflight.com/docs/android) to view an updated list.


Looking for iOS?
-----------------

We've got you covered. [Click here](https://github.com/CardFlight/cardflight-ios) to learn more about our CardFlight iOS SDK.

