# Lenovo-Tab-M10-Plug-Gen-3-FlashiGSI-roms

This is a guide on how to flash GSI custom roms on the Lenovo Tab M10 Plus Gen3 (FU125 or Maple)


1)Install tablet drivers on your computer


Download drivers zip and extract
Plug tablet into computer
Open Device Manager
You’ll see a line item labeled “ANDROID” with a yellow exclamation mark
Right click on it and select update drivers
Select Browse Computer and navigate to the unzipped driver folder
Make sure the Include Subfolders box is checked and select Next
This will install the drivers for the tablet, if you have any issues where the tablet is not recognised in the following steps
go back into the device manager, and see if there is other driver needed to install from thius folder (ie fastboot)


2) Unlock your tablet's developers options and enable debugging and oem unlock


Open settings on your tablet
Search for “build”
Click “Build Number”
Click the Build Number box seven times to unlock developer options
Close and reopen the settings app
Under System there is now a Developer options, open it
Toggle the selections for OEM Unlocking and USB debugging
IF plugged to the computer, it will promptly ask to approve debugging from this Device, press Always - OK

  
3) Download suitable GSI Rom
visit https://github.com/phhusson/treble_experimentations/wiki/Generic-System-Image-%28GSI%29-list
download an ARM64 image (Android 13 Official or as a second option Unofficial) you can also flash older Android images
extract img file from zip
