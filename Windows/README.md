# Windows Bad USB Scripts

This section of the repository contains scripts tailored specifically for Windows operating systems, designed to leverage the Flipper Zero's Bad USB functionality for Ethical purposes.

---

| Name                            | Description                              |  USB  | BLE  |
|---------------------------------|------------------------------------------|--------------|--------------|
| [wifi-dump.txt](wifi-dump.txt)  | Extracts saved Wi-Fi SSID and passwords and stores them locally, in the `Documents` folder | ✅ Yes       | ❓  Not Tested        |

---

## 🚀 How to Use via USB  

1. **Copy the Payload**: Transfer the desired `.txt` file(s) to your Flipper Zero device.  
2. **Connect to Target**: Plug your Flipper Zero into the target Windows system via USB.  
3. **Run the Payload**: Navigate to the **Bad USB menu** on the Flipper Zero and select the script.  
4. **Enjoy the Magic**: Observe as the script automates tasks or demonstrates vulnerabilities.  

---

### 🚀 How to Use via BLE  

1. **Prepare the Payload**: Transfer the desired `.txt` file(s) to your Flipper Zero device.  
2. **Activate BLE Mode**: Enable Bluetooth on your Flipper Zero via the **Bluetooth Settings** menu.  
3. **Pair with Target**: Use a mobile device or computer to pair with the Flipper Zero as a Bluetooth keyboard.  
   - **On Windows**: Go to *Settings > Devices > Bluetooth & Other Devices* and add a new device.  
   - Select the Flipper Zero from the list of available devices.  
4. **Run the Payload**: Navigate to the **Bad USB menu** on the Flipper Zero, select the script, and execute.  
5. **Watch it Work**: The payload will be executed over Bluetooth as if a physical keyboard was connected.  


## 📜 License  

This project is licensed under the **[GNU GPLv3](../LICENSE)** to ensure that all contributions remain free and open source.  
