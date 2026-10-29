## Part 1: Hardware Setup (M5Stick C Plus 2)
This section explains how to upload the firmware to your M5Stick C Plus 2 device.

### Prerequisites:
* M5Stick C Plus 2 device.
* USB-C cable.
* A computer or laptop with the **Arduino IDE** installed.
* (Windows users) CP210x USB to UART Bridge VCP Drivers installed.
* The **M5Stack board manager** installed in the Arduino IDE.

### Step-by-Step Instructions:
1. Plug the M5Stick C Plus 2 into your computer using the USB-C cable.
2. Press the left button (power button) on the M5Stick to turn it on.
3. Launch the Arduino IDE on your computer.
4. Go to **Tools > Board > M5Stack** and select **M5Stick-C**.
5. Go to **Tools > Port** and select the correct COM port for your device.
6. In the Arduino IDE, go to **File > Open** and navigate to the `m5_firmware/sketch_nov21a` folder in your downloaded project files. Open the `.ino` file.
7. If the code requires specific libraries, go to **Sketch > Include Library > Manage Libraries**, search for `M5StickCPlus2` or `M5Unified`, and click Install.
8. Click the **Upload button** (the right-pointing arrow icon ➔) at the top left of the Arduino IDE.
9. Wait for the "Done uploading" message. The M5Stick screen should now display the startup screen for the i-Sleep project.

---

## Part 2: Android App Installation
This section explains how to install and run the mobile application.

### Prerequisites:
* An Android smartphone or an Android Emulator.
* The `.apk` file OR the source code.
* A computer with Visual Studio Code and Flutter installed.

### Step-by-Step Instructions: Running via Source Code
1. Download the entire project repository as a `.zip` file from GitHub and extract it.
2. Open Visual Studio Code and go to **File > Open Folder** and select the extracted `i-Sleep-senior-iot-project` folder.
3. Go to **Terminal > New Terminal**.
4. Type `flutter pub get` and press Enter.
5. Connect your Android phone via USB (ensure USB Debugging is enabled) OR start an Android Emulator in VS Code.
6. Type `flutter run` in the terminal and press Enter. Wait for the app to build and launch on your device.
