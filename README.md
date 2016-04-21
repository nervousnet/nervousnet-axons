# Nervousnet Axons
Axons let you visualise and manipulate your phones sensor data using the [nervousnet Android](https://github.com/nervousnet/nervousnet-android) or [iOS](https://github.com/nervousnet/nervousnet-iOS) apps. You can get Axons from the __nervousnet Space__ accessible within the apps. Axons are not standalone applications and cannot run without the nervousnet Android or iOS app.


## How to Make an Axon
Take a look at the example axon, fork and modify it:
   1. Fork [Example Axon](https://github.com/bitmorse/axon-one).
   2. Modify your axon by changing `axon.html` and `axon.js` to do what you like.
       * A [UI framework]( http://code.kik.com/app/3/index.html) is included for your convenience.
       * You may use a local browser to test the Axon, although the special URLs below and the included libs.js will only be available on your phone at this time.
       * Testing Axons on the phone is easy, as your code is redownloaded from your GitHub repo when you press the special refresh button  (this is why step 1 is important).
   3. Submit `package.json` [here](https://github.com/nervousnet/nervousnet-axons/issues/new) and it will be added to the *nervousnet Space* in the Android and iOS apps by us.
   4. Download and install your Axon from the *nervousnet Space* in the Android and iOS apps.

## Getting Sensor Data from Your Phone
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

## Debugging Axons
   1. Open the Axon in the nervousnet app on your phone or simulator.
   2. Open Safari and [enable the develop menu](http://macs.about.com/od/usingyourmac/qt/safaridevelop.htm).
   3. Go to "Develop" and select your phone or simulator (see screenshot), then the axon.html page.
   4. An inspector will open, with which you have full debugging access (editing code, breakpoints, network analysis, etc). This is also where you'll see console.log messages.
   ![safari](https://i.imgur.com/Q7XcwH7.png)

   ![inspector](https://i.imgur.com/MlBa6TD.png)
