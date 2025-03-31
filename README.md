# Standalone MP3 Player

This project is a **standalone MP3 player** using an MP3 SD card module, Cherry MX switches for media control, a LiPo battery for portability, and a TP4056 charging module. It’s a simple, ad-free way to listen to music from a microSD card without needing any coding or complex setup. Just load music, connect the components, and enjoy!

### Features:
- **No Code Required**: This MP3 player works with a standalone MP3 decoder board (no programming needed).
- **Physical Media Controls**: Cherry MX switches for controlling play/pause, next track, previous track, and volume.
- **Rechargeable**: LiPo battery with a TP4056 module for easy charging.
- **Portable**: Compact and lightweight design, perfect for on-the-go listening.

## Components Used:
Here’s a list of the key parts used in building the MP3 player, with links to the product pages:

### 1. **MP3 SD Card Module**
   - **Description**: This is the core module that allows you to play MP3 files from a microSD card. It handles all audio decoding and playback, so there’s no need for additional code or complex setup.
   - **Link**: [MP3 SD Card Module on AliExpress](https://www.aliexpress.us/item/3256806504625045.html?spm=a2g0o.order_list.order_list_main.29.571c1802PPjZk1&gatewayAdapt=glo2usa)

### 2. **Cherry MX Mechanical Switches**
   - **Description**: Cherry MX switches are used for media control buttons, including play/pause, next, previous, and volume control. They provide tactile feedback and a satisfying user experience.
   - **Link**: [Cherry MX Switches on AliExpress](https://www.aliexpress.com/store/1102696782?spm=a2g0o.order_list.order_list_main.104.571c1802PPjZk1)

### 3. **LiPo Battery (Salvaged from Nicotine Vape)**
   - **Description**: A rechargeable LiPo battery salvaged from a nicotine vape provides portable power to the MP3 player.
  

### 4. **TP4056 LiPo Charging Module**
   - **Description**: This module charges the LiPo battery safely, with built-in protection for overcharging and overdischarge.
   - **Link**: [TP4056 Module on Amazon](https://www.amazon.com/dp/B075RDYMQQ?ref=ppx_yo2ov_dt_b_fed_asin_title)

### 5. **Toggle Switch**
   - **Description**: A simple toggle switch is used to turn the MP3 player on and off.

### 6. **microSD Card**
   - **Description**: The microSD card stores the MP3 music files that you will play on the device.

### 7. **3D Printed Enclosure**
   - **Description**: The components are housed in a custom 3D-printed enclosure, making the device compact and portable.
   - **File**: STL file for the 3D printed case is available in the repository.

---

## How to Assemble:

### 1. **Assemble the Hardware**
   - **MP3 SD Card Module**: Connect the module to the microcontroller or directly to the speaker as per the pinout. This module is responsible for decoding and outputting audio from the microSD card.
   - **Cherry MX Switches**: Connect the switches to the designated pins (for play/pause, next track, previous track, volume up/down).
   - **LiPo Battery & TP4056 Module**: Connect the LiPo battery to the TP4056 module. The charging port allows you to recharge the battery.
   - **Power Switch**: Attach the toggle switch to the power input to turn the device on/off.

### 2. **Load Music onto the microSD Card**
   - Format the microSD card and load your MP3 files onto it.
   - The MP3 player will automatically detect the files and begin playback from the microSD card once powered on.

### 3. **Assemble the Enclosure**
   - Print the 3D enclosure using the provided STL files.
   - After printing, assemble the components inside the enclosure, ensuring all buttons and connectors are accessible.

---

## How to Use:

1. **Load MP3 Files**: Format your microSD card and load MP3 files into it. 
2. **Power On**: Use the toggle switch to power on the MP3 player.
3. **Control Playback**: Use the Cherry MX switches to control the media:
   - **Play/Pause**: Toggle play/pause with the corresponding switch.
   - **Next/Previous**: Skip to the next or previous track.
   - **Volume**: Increase or decrease the volume by long pressing the Next/Previous Buttons.

---

## Troubleshooting:

- **No Sound**: Ensure the speaker is properly connected to the MP3 module, and the volume is turned up.
- **Battery Not Charging**: Verify that the LiPo battery is correctly connected to the TP4056 module. Check that the charging cable is inserted properly.
- **Buttons Not Working**: Double-check the wiring for the Cherry MX switches and ensure that they are connected to the correct pins on the MP3 module.

---

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

Feel free to reach out if you have any questions or issues!
