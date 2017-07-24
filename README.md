# kicad-lib
KiCad component library

All contributions should adhere to the Kicad library convention, just like the standard KiCad library. See: https://github.com/KiCad/kicad-library/wiki/Kicad-Library-Convention

## Usage

In order to use this library in an convenient and efficient manner, there are some configurations that should be made to your KiCad installation.

Start by cloning the library to a local copy on your computer. I.e. by issuing: ```git clone https://github.com/switchcraft/kicad-lib.git```.

In the main KiCad project browser, select Preferences -> Configure paths. In the appearing window, add a new path with the name SWITCHCRAFTLIB, and the absolute path to your cloned version of the git repository.

This will allow any projects to simply refer to this variable for the location of custom libraries, and simplify portabillity. 

Additionally you might want to configure the KICAD_PTEMPLATES path to point to the template subdirectory of this repository.

## Templates

If the library is correctly configured, you should be able to create new projects using the menu option File -> New project -> New project from template. Select a suitable location for your new project, and the "Project Template Selector" will appear. The "Portable Templates" tab will allow you to select the custom templates.
