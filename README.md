# gcamxml
A guide to import custom XML settings into google camera ports

Config files are stored in the **/GCam/Configs/** directory. This folder needs to be created manually using a file manager or automatically by exporting your config (use the option in settings menu). Config files use the .xml extension.

1. Get the latest [GCam build](https://www.celsoazevedo.com/files/android/google-camera/dev-arnova8G2/)

2. On your storage create a folder at this path:

    - **GCam/Configs** ([See Screenshot](https://github.com/H1XYZ/gcamxml/blob/master/!storage_path.jpg))
    - [Download](https://github.com/H1XYZ/gcamxml?files=1) & put the XML files in that config folder

3. Go back to the google camera app and import an XML

    - Double tap on the import area ([See Screenshot](https://github.com/H1XYZ/gcamxml/blob/master/!xml_toggle_import.jpg))
    - Select the XML of choice
    - Click Restore

Done

Export/Save:
To backup your settings, use the option available in the settings menu. Your configuration will be saved in the default /GCam/Configs/ folder (eg: **/GCam/Configs/config-name.xml**). This file can be used on another GCam version that supports this feature or shared with other users.

Notes:
 - RAW SENSOR setting has a bug at the moment that causes crashes in selfie mode
 - RAW10 XMLs are good daily drivers with little to no crashes
 - App crashing? Go to **Settings > Advanced > Fix** | Set **RAW Format** to **RAW10** | Set **Viewfinder Format** to **JPEG**
 - Motion Function not working? Set **RAW Format** to **RAW SENSOR** 
