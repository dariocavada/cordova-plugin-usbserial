## cordova-plugin-usbserial



Just starting... whatch the project if you would like to be notified when a first version will be available. 



## Change log
2018.02: [Dario Cavada] (https://github.com/dariocavada): renamed to cordova-plugin-usbserial and refactory internal to follow cordova naming convention

2015.10: [Ed. Lafargue](https://github.com/elafargue): Implemented "sleepOnPause" flag in the 'open' options to prevent closing the OTG port when app goes to background.

2014.08: [Zevero](https://github.com/zevero): Option to find device by VID and PID, that let you use "unrecognized" devices.

2014.07: [Hendrik Maus](https://github.com/hendrikmaus): Implemented writeHex for working with RS232 protocol, i.e. javascript can now pass "ff", java turns it into a 1 byte array and writes to the serial port - naturally, java, and the existing write method here, would create a 2 byte array from the input string.

2014.04: [Derek K](https://github.com/etx): Implemented registerReadCallback for evented reading and Android onPause/onResume
         
2014.03: [Ed. Lafargue](https://github.com/elafargue): Implemented read(). The success callback returns a Javascript ArrayBuffer which is the best way to handle binary data in Javascript. It is straightforward to convert this to a string if required - a utility function could be implemented in this plugin.

2013.11: [Xavier Seignard](https://github.com/xseignard): First implementation
