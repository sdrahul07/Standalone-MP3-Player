# Standalone MP3 Player

![Screenshot 2025-03-31 135758](https://github.com/user-attachments/assets/e89cda98-00b3-4386-a0f5-6868412b6618)
![Screenshot 2025-03-31 135745](https://github.com/user-attachments/assets/2b216e62-6aea-4055-a205-999712443104)

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
   - **Link**: [MP3 SD Card Module on AliExpress]([https://www.aliexpress.us/item/3256806504625045.html?spm=a2g0o.order_list.order_list_main.29.571c1802PPjZk1&gatewayAdapt=glo2usa](https://www.aliexpress.us/item/3256806504625045.html?spm=a2g0o.order_list.order_list_main.77.4c8e194d9vosQF&gatewayAdapt=glo2usa))

### 2. **Cherry MX Mechanical Switches**
   - **Description**: Cherry MX switches are used for media control buttons, including play/pause, next, previous, and volume control. They provide tactile feedback and a satisfying user experience.
   
### 3. **LiPo Battery (Salvaged from Nicotine Vape)**
   - **Description**: A rechargeable LiPo battery salvaged from a nicotine vape provides portable power to the MP3 player.
  

### 4. **TP4056 LiPo Charging Module**
   - **Description**: This module charges the LiPo battery safely, with built-in protection for overcharging and overdischarge.
   - **Link**: [TP4056 Module on Aliexpress](https://www.aliexpress.us/item/3256805951432581.html?spm=a2g0o.productlist.main.15.1f867ef7Fm7euQ&aem_p4p_detail=202503311151511909936599042420003208703&algo_pvid=0c51f7a6-e80b-40e0-8077-77299e075838&algo_exp_id=0c51f7a6-e80b-40e0-8077-77299e075838-7&pdp_ext_f=%7B%22order%22%3A%22454%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%211.69%211.69%21%21%2112.24%2112.24%21%402101c80217434471117815703e0a25%2112000035928826208%21sea%21US%212492344101%21X&curPageLogUid=OqC47eT556Zf&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202503311151511909936599042420003208703_2))

### 5. **Toggle Switch**
   - **Description**: A simple toggle switch is used to turn the MP3 player on and off.
   - **Link**: [Toggle Switch on Amazon](https://www.amazon.com/dp/B075RDYMQQ?ref=ppx_yo2ov_dt_b_fed_asin_title)

### 6. **Speaker**
   - **Description**: Just a enclosed speaker I found on Aliexpess that was compact enough for the projects ( ensure that the one you use is 4Ohm and 3W)
   - **Link**: [Speaker on Aliexpress](https://www.aliexpress.us/item/3256805513376202.html?spm=a2g0o.order_list.order_list_main.149.4c8e194d9vosQF&gatewayAdapt=glo2usa)

### 7. **3D Printed Enclosure**
   - **Description**: The components are housed in a custom 3D-printed enclosure, making the device compact and portable.
   - **File**: STL file for the 3D printed case is available in the repository’s `hardware/` folder.

---

## How to Assemble:

### 1. **Assemble the Hardware**
   - **MP3 SD Card Module**: Connect the module to the microcontroller or directly to the speaker as per the pinout. This module is responsible for decoding and outputting audio from the microSD card.
   - **Cherry MX Switches**: Connect the switches to the designated pins (for play/pause, next track, previous track, volume up/down).
   - **LiPo Battery & TP4056 Module**: Connect the LiPo battery to the TP4056 module. The charging port allows you to recharge the battery.
   - **Power Switch**: Attach the toggle switch to the power input to turn the device on/off.
   - **Speaker**: Connect the speaker to the MP3 SD Card Module on the provided solder pads.

### 2. **Load Music onto the microSD Card**
   - Format the microSD card and load your MP3 files onto it.
   - The MP3 player will automatically detect the files and begin playback from the microSD card once powered on.

### 3. **Assemble the Enclosure**
   - Print the 3D enclosure using the provided STL file in the `hardware/` folder.
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
