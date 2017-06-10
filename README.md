# node-simconnect
Wrapper for the SimConnect SDK for FSX and Prepar3D (Windows)

This project is at a very early stage and only covers a few SimConnect function calls. Feel free to join the development :)

## Build
### Requirements
* Node.js (32-bit version)
* Visual Studio 2013 (32-bit version)
* FSX or P3D SimConnect SDK files (.lib and .h). 

NOTE: If your app need to work with both FSX and P3D you must use the FSX SDK.

### Setup
* Create a folder named `SimConnect` and copy the two folders `inc` and `lib` from the SimConnect SDK installation over to the new directory. These should include `SimConnect.h` and `SimConnect.lib`, respectively.
* Run `npm install`
* If everything went well you should be able to run the example program using: `node example`