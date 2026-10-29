#i-sleep

Welcome to the i-Sleep IoT Project. This system consists of two parts:
- M5Stick C Plus 2 (Hardware): The physical sensor device.
- Android Application (Software): The mobile app used to monitor the data

Part 1: Hardware Setup (M5Stick C Plus 2)
This section explains how to upload the firmware to your M5Stick C Plus 2 device.

Prerequisites:
- M5Stick C Plus 2 device.
- USB-C cable.
- A computer or laptop with internet access.
- UIFlow Web IDE (or Arduino IDE) installed.

Step-by-Step Instructions:
1 Plug the M5Stick C Plus 2 into your computer using the USB-C cable.
2 Press the left button (power button) on the M5Stick to turn it on.
3 Go to flow.m5stack.com in your web browser.
4 Click the "Connect" button in the bottom right corner of the screen and select the correct COM port for your M5Stick.
5 Upload Firmware.
6 Locate the sketch_nov21a file from the project repository.
7 Copy the code from the file.
8 Paste the code into the workspace in the IDE.
9 Click the Run (▶) button to upload the code to the device.
10 Once uploaded, the M5Stick screen should display the startup screen for the i-Sleep project.


Part 2: Android App Installation
This section explains how to install and run the mobile application.

Prerequisites:
- An Android smartphone or an Android Emulator.
- The .apk file or the source code.
- A computer with Visual Studio Code and Flutter installed.

Step-by-Step Instructions:
Running via Source Code
1 Download the entire project repository as a .zip file from GitHub and extract it.
2 Open Visual Studio Code and go to File > Open Folder and select the extracted i-Sleep-senior-iot-project folder.
3 Go to Terminal > New Terminal.
4 Type flutter pub get and press Enter.
5 Connect your Android phone via USB (ensure USB Debugging is enabled) OR start an Android Emulator in VS Code.
6 Type flutter run in the terminal and press Enter. Wait for the app to build and launch on your device.
