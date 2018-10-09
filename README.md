# Android-nRF-UART-Bridge

nRF UART Bridge app can be used to connect to Bluetooth® Smart devices running a custom Nordic Semiconductor UART service. 
When connected, the app bridges the UART port with TCP port, so an Android device can be used as a BLE interface over WiFi or USB.

This source code can be compiled with Android Studio and Gradle. 

Based on Android-nRF-UART app by Nordic Semiconductor.

## Usage

- Install apk, start the app
- Connect to BLE device
- ADB USB:
  - Forward TCP port 6000 with adb: *adb forward tcp:6000 tcp:6000*
  - Connect to localhost:6000 
- WiFi:
  - Connect to IP:port shown in the app
- Send/receive data - this will be forwarded to/from BLE device  

### Note
- Android 4.3 or later is required.
- Android Studio supported 
