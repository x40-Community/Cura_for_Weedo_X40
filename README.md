# Ultimaker Cura Configuration for WEEDO X40
![image](http://www.x40-community.org/images/x40/cura.jpg)

## Weedo X40
Since Weedo didn't provide a really well-working configuration for Ultimaker Cura after the Kickstarter project, the X40 community got to work. Thanks to donations, a good setup with many printer profiles could be created.
However, the project always struggled with errors in the firmware. In particular, the problem with heating up in dual mode could only be improved with a workaround, but not eliminated.

For the perfect operation of the Weedo X40 with Ultimaker Cura, the X40 PRO project with the adaptation of the firmware to Ultimaker Cura.

## Ready to use
The X40 Community Cura configuration is much more than just a printer definition. It contains a printer visualization and hundreds of tested print profiles. Simply select a supported filament, make small adjustments such as support structure etc. and just print. There is no need to search for and test the correct print parameters. 

Here you can see the supported filament and the current status: Cura Quality and Intent Profiles

Standard configuration for Weedo X40 or other Firmware
- Available for Cura 4.X and 5.X
- Full Idex printing support (Single LH, Single RH, dual mode normal, dual mode mirrored, copy mode) up start script Rev. 11
- The configuration contains about 3000 print profiles.
- Supported nozzle size 0,4mm and 0,6mm (not for all printing profiles)
- The Cura plugin for embedding the printer preview image is not part of the configuration!

More Information see http://www.x40-community.org/index.php/cura/cura-configuration

## Help
Please note that support is only available for X40 community members. Questions on github will therefore not be answered.
You can join the X40 community at: http://www.x40-community.org/index.php/members-area

A Cura crash does not necessarily mean that the configuration is defective. Normally, the user is just too dumb to do so because not everything has been taken into account!

## Supported Cura Version 
- Ultimaker Cura 4.8
- Ultimaker Cura 4.9
- Ultimaker Cura 4.10
- Ultimaker Cura 4.11
- Ultimaker Cura 4.12
- Ultimaker Cura 4.13
- Ultimaker Cura 5.0.0

The Configuration doesn't work together with Weedo Cura! 

## Supported Hardware Version 
- X40 V1: The first mass production version. The production time is from November 2020 to June 2021.
- X40 V2: The second production version. The production batch start from July 2021.


## Information
**The configuration will not be developed further. Please use the Weedo X40 PRO Cura configuration and X40 PRO firmware if you want use the latest Cura Version. The plugin is not part of the configuration and is only available to X40 community members.**

## Install
Download the Zip-file from the github server. The zip file for Cura 4.12 / 4.13 / 5.0.0 can only be used with Cura 4.12.X / 4.13.X / 5.0.0. So make sure you have the right version! Unzip the zip file and look for the resources directory.  

The configuration files, materials and printing profiles for the Weedo X40 can be found in the following subdirectories: 

    definitions
    extruders
    intent
    materials
    meshes
    quality
    variants

Now look for the resources directory on your PC from your Cura installation.

    Windows
    Cura 4.X (C:\Program\Ultimaker Cura 4.13\resources)
    Cura 5.X (C:\Program Files\Ultimaker Cura 5.0.0\share\cura\resources)

    Linux
    /usr/share/cura/resources
    or
    ~/.local/share/cura/4.13



    MacOS 
    (In Finder go to the application folder, find Cura 4.13, right click in the application, open show contents, contents, MacOS, resources)

 

Copy the complete content from the Zip-file into the resources directory of the Cura installation and restart Cura.
