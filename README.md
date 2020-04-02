# HuaweiQuickApp-WebviewSample
Huawei Quick App Sample featuring WebView feature

<kbd>
  <img src="pictures/QuickApp_WebView.jpg" height="600"/>
</kbd>

## How to use

### Install Quick App development tools

Follow the instructions on the Huawei Quick App Guide to install the Quick App IDE.
https://developer.huawei.com/consumer/en/doc/development/quickApp-Guides/quickapp-installtool#h1-1578317695350

Make sure to install the Huawei Quick App Loader on the test device.
https://developer.huawei.com/consumer/en/doc/development/quickApp-Guides/quickapp-installtool#h1-1578318207348

### Run on USB connected Device

Ensure that USB connected device has Huawei Quick App Loader installed as well as USB debugging enabled.

<kbd>
  <img src="pictures/QuickAppLoader_installed.jpg" height="600"/>
</kbd>



### Create a standalone RPK file

To build the RPK file, go to Build > Run Release

<img src="pictures/build_release.png" height="600"/>

Press OK to confirm settings and start build.

<img src="pictures/build_cert.png" height="500"/>

The RPK file is located in the /dist/ folder found in the root of the project. This file can be shared and run on any test device that has the Huawei Quick App Loader installed. Some email services may block incoming/outgoing emails with attached RPK files, and an alternative file sharing method is recommended.

### Run the RPK file

Connect the test device via USB and ensure that the USB settings have been set to file transfer.

<kbd>
  <img src="pictures/device_downloads.jpg" height="500"/>
</kbd>
