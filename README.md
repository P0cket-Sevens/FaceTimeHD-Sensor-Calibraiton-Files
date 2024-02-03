# FaceTimeHD Sensor Calibraiton Files

These files are the FaceTime Sensor Calibration files extracted from the Windows Bootcamp Drivers.  These files should correct the colors of your Apple FaceTime camera on Linux.

The files were extracted using the following instructions:  https://github.com/patjak/facetimehd/wiki/Extracting-the-sensor-calibration-files

Installation:
1. After you've installed the FaceTime Linux Driver, go to the release page and either download each individual DAT file or download the zip file "FacetimeHD_Sensor_Calibration.zip".

2. If you've downloaded the ZIP file, extract the individal DAT files from the ZIP file.

3. Move the DAT filse to the facetimehd firmware directory using the following command:  sudo mv ~/Downloads/*.dat /lib/firmware/facetimehd/

4. Optional step:  enter the following commands to confirm the DAT files were copied properly:

cd /lib/firmware/facetimehd

ls -la

You should see all 4 DAT files in the folder.

**NOTE** You may need to restart your system to load the new sensor calibration files.

For installing the FaceTime Linux Driver, I highly recommend going to PatJak's page and following his instructions:  https://github.com/patjak/facetimehd

NOTE:  Use these files at your own risk.  While I make these files available for general use, and I use them myself (and find they help with the color correction), I make no warranty as to their effectiveness.
