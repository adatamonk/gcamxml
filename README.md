# gcamxml
A guide to import custom XML settings into google camera ports

Config files are stored in the **/GCam/Configs/** directory. This folder needs to be created manually using a file manager or automatically by exporting your config (use the option in settings menu). Config files use the .xml extension.

1. Get the latest [GCam build](https://www.celsoazevedo.com/files/android/google-camera/dev-arnova8G2/)

2. On your storage create a folder at this path:

    - **GCam/Configs** ([See Screenshot](https://github.com/H1XYZ/gcamxml/blob/master/!storage_path.jpg))
    - [Download](https://github.com/H1XYZ/gcamxml/archive/master.zip) & extract the XML files in that config folder

3. Go back to the google camera app and import an XML

    - Double tap on the import area ([See Screenshot](https://github.com/H1XYZ/gcamxml/blob/master/!xml_toggle_import.jpg))
    - Select the XML of choice
    - Click Restore

Done

Export/Save:
To backup your settings, use the option available in the settings menu. Your configuration will be saved in the default /GCam/Configs/ folder (eg: **/GCam/Configs/config-name.xml**). This file can be used on another GCam version that supports this feature or shared with other users.

XML Recommendations:

Overall:
- V1RUS-GLib-Standard (warmer shot)
- V1RUS-GLib-Standard-NS (colder shot + night sight)

Day Use:
- V1RUS-GLib-R10-P3XL (deeper colors, warmer)
- V1RUS-GLib-R10-PXL (natural colors, colder)
- V1RUS-GLib-RS-P3XL (no selfies)
- V1RUS-Esz4-RAW10 (neutral colors, more noise)

Night Sight:
- V1RUS-NS-R10
- V1RUS-NS-RS (less noise)

Notes:
 - RAW10 has better focus in low light and no front camera crash issues (good for daily use)
 - RAW_SENSOR produces better shots with the Back Camera (no blue tint, better whitebalance) but it will lead to Front Camera Crashes
 - There is now a Auto White-Balance (AWB) Toggle which enables/disables the Pixel 3 AWB AI. I would recommend to enable the toggle (which turns the AWB off). Gives more natural whitebalance
 - Set Back Camera to "Pixel XL" instead of "Pixel 3 XL", it fixes the yellow tint issue
 - XMLs with "NS" are designed to be used in Night Sight mode (low light) only
 - App crashing? Go to **Settings > Advanced > Fix** | Set **RAW Format** to **RAW10** | Set **Viewfinder Format** to **JPEG**
 - Motion Function not working? Set **RAW Format** to **RAW SENSOR** 
