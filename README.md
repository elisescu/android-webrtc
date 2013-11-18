android-webrtc
==============

Simple webrtc client for Android taken from libjingle source code and compiled separately.
It contains both the native and the JNI wrapper for libjingle (`./lib/`).

- **update** the project to generate the `build.xml` file. Example for API-17:

  ```bash
  android update project -p . -t android-17
  ```
- **build** the project using ant (or import it to Eclipse/IntelliJ). Example for debug build:

 ```bash
  ant debug
  ```
- **install** the apk just built:

  ```bash
  adb install ./bin/AppRTCDemoActivity-debug.apk
  ```

- Note: currently the native library is compiled just for ARM.
