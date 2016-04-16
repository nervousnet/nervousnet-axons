#### WORKING DRAFT. ANYTHING IN THIS DOCUMENT CAN CHANGE UNEXPECTEDLY.

# Nervousnet Axons
Axons let you visualise and manipulate your phones sensor data using the [nervousnet Android](https://github.com/nervousnet/nervousnet-android) or [iOS](http://nervousnet.github.io/nervousnet-iOS) apps. You can get Axons from the __nervousnet Space__ accessible within the apps. 


## How to Make an Axon
Take a look at the example axon, fork and modify it:
   1. Fork [Example Axon](https://github.com/bitmorse/axon-one).
   2. Modify your axon by changing `axon.html` and `axon.js` to do what you like.
       * A [UI framework]( http://code.kik.com/app/3/index.html) is included for your convenience.
       * You may use a local browser to test the Axon, although the special URLs below will only work on your phone.
       * Testing Axons on the phone is easy, as your code is redownloaded from your GitHub repo when you press the special refresh button  (this is why step 1 is important).
   3. Submit `package.json` [here](https://github.com/nervousnet/nervousnet-axons/issues/new) and it will be added to the *nervousnet Space* in the Android and iOS apps by us.
   4. Download and install your Axon from the *nervousnet Space* in the Android and iOS apps.

## Getting Sensor Data from Phone
Call these local URLs from within the Axon code to get real time sensor data of your phone
   * http://localhost:8080/nervousnet-api/raw-sensor-data/GPS
   * http://localhost:8080/nervousnet-api/raw-sensor-data/Accelerometer
   * http://localhost:8080/nervousnet-api/raw-sensor-data/Magnetometer
   * http://localhost:8080/nervousnet-api/raw-sensor-data/Gyroscope
   * http://localhost:8080/nervousnet-api/raw-sensor-data/BLE

## Documentation
   * [Nervousnet Android App Docs](https://github.com/nervousnet/nervousnet-android/tree/master/Documents)
   * [Nervousnet iOS App Docs](https://github.com/nervousnet/nervousnet-iOS/blob/master/README.md)

## Submitting Axons to Nervousnet Space
   1. Fork this repository.
   2. Add your axon's `package.json` under a __new name__ in the `contrib` or `testing` directory. __Note__: Axons added to the `testing` directory are immediately available on the Testflight version of the app.
   3. Send us a [pull request](https://yangsu.github.io/pull-request-tutorial/) and your axon will be available shortly.
