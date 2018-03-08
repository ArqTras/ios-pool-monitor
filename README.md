# Pool Monitor

An Apache Cordova & AngularJS application to monitor mining stats for all major TurtleCoin mining pools running CryptoNote.

Using Pool Monitor you can get all the details regarding your TurtleCoin mining like hashrate, payments, and more.

Features:
* Easy. Just add your wallet address and, voil�, you'll have all of the details.
* Reliable. Pool Monitor doesn't collect or save any data on your device.
* Safe. All APIs used are safe and verified by multiple developers and miners.
* Open source. Pool Monitor is free and open source, enabling anyone to verify its security by auditing the code.

## List of Pools Supported
Currently the app supports the following pools:

* [us.turtlepool.space](http://us.turtlepool.space)
* [z-pool.com](http://z-pool.com)
* [slowandsteady.fun](http://slowandsteady.fun)
* [eu.turtlepool.space](http://eu.turtlepool.space)
* [hk.turtlepool.space](http://hk.turtlepool.space)
* [ny.minetrtl.us](http://ny.minetrtl.us)
* [auspool.turtleco.in](http://auspool.turtleco.in)
* [pool.turtleco.in](http://pool.turtleco.in)
* [trtlpool.ninja](http://trtlpool.ninja)
* [pool.trtl.me](http://pool.trtl.me)
* [cryptoknight.cc](http://cryptoknight.cc)
* [trtl.ninja](http://trtl.ninja)
* [sewer.ninja](http://sewer.ninja)
* [turtlecoinpool.ml](http://turtlecoinpool.ml)

-------------------------

# Build Steps

## Prerequisites
 - Apple Xcode
 - Apple iOS Developer Account
 - node ([nodejs.org/en/](https://nodejs.org/en/))
 - npm (if you installed node using an .msi , .exe , .dmg .pkg , .deb or using a package installer like apt-get , yum or brew, then you'll have both node and npm)
 - cordova `sudo npm install -g cordova`
 - ios-deploy `npm install -g ios-deploy`
 - cocoapods `sudo gem install cocoapods`

You can run the following to be sure you have the necessary prerequisites to build the project for iOS:
```
cordova requirements
```

## To run / test in the Simulator:
1. `cd pool-watcher`
2. `cordova platform add ios`
3. `cordova run ios --target="iPhone-X"`

You can use the following to see all available targets:
```
cordova run ios --list
```

## Additional Notes

You can also run the application in a web browser by using a local web server with the web root set to:
```
pool-watcher/www/
```

To build and/or run manually open this file in Xcode:
```
pool-watcher/platforms/ios/TRTL Pools.xcodeproj
```

You can build using the CLI with this command from pool-watcher/, but I haven't worked with it before:
```
cordova build ios
```

To propagate any changes in the app source and assets in www into the Xcode project file, run this command from pool-watcher/:
```
cordova prepare
```

-------------------------

## Contributing

Please read [CONTRIBUTING](https://github.com/derp-derp-derp/Turtle-Coin-Pool-Watcher/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests.

## Author

* [derp-derp-derp](https://github.com/derp-derp-derp)

## Donating TRTL
If you found the app useful, TRTL is always greatly appreciated:
`TRTLv3m5HxMBpoJDyNFwYB7P9L4hE5ve7NshZio2GuFqRn6SDFMcZX5QPEwexAib45YV6gFrnEpkABPT8nAdGoqD16Xtv8e2xx7`

## License

This project is licensed under the GNU LGPL - see the [LICENSE](https://github.com/derp-derp-derp/Turtle-Coin-Pool-Watcher/blob/master/LICENSE.md) file for details.

## Acknowledgments and Thanks

* [Forknote Pool & Pool API Software](https://github.com/forknote/forknote-pool)
* The Entire Turtle Coin Community
* Aditya Gupta & Hemant Joshi - Developers of [Pool Watcher for Android](https://github.com/turtlecoin/android-pool-monitor)