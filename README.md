# ClassicWB ADV Package

ClassicWB ADV is a feature rich Workbench enhancement by Bloodwych targeted A1200 with 4MB memory expansion using 16 colour screenmode using Multisync / Interlaced 640x512 display.

## Description

ClassicWB ADV Package contains ClassicWB ADV v28 created by Bloodwych from EAB.

With permission from Bloodwych it has been converted to a package for HstWB Installer.

Original version of ClassicWB ADV can be downloaded from http://classicwb.abime.net/.

## Requirements

ClassicWB ADV package can be installed on any Amiga with Workbench 3.1 and about 108MB free space on a harddrive for installation.

## Installation

Download latest release from https://github.com/henrikstengaard/classicwb-adv-package/releases and copy it to HstWB Installer "packages" directory, which typically is "c:\Program Files (x86)\HstWB Installer\Packages".

Installation through HstWB Installer will install and configure ClassicWB ADV package using defined assigns.
During installation dialogs are presented to customize ClassicWB installation.

## Assigns

Installation of ClassicWB ADV package requires and uses following assign and default value:

- SYSTEMDIR: = DH0:

ClassicWB ADV files will be installed and configured in SYSTEMDIR: assign, which must be set to harddrive containing Workbench.

## Modifications

ClassicWB is installed from a zip file containing all files from ClassicWB System.hdf.

The install script for HstWB Installer is based on S/Startup-Sequence from ClassicWB System.hdf with following changes:

- Removed Workbench installation.
- Paths has been changed: SYS: to SYSTEMDIR:, C: to SYSTEMDIR:C/, L: to SYSTEMDIR:L/.
- Modified versions of Temp enable and disable option scripts with changed paths.
- Removed all "press enter to continue" expect last one used after installation complete message is shown.
- Removed and reduced waits.
- Adjusted text spacing.

## Screenshots

Screenshots of ClassicWB ADV from http://classicwb.abime.net/classicweb/advpics.htm.

![ClassicWB ADV 1](screenshots/classicwb_adv1.png?raw=true)

![ClassicWB ADV 2](screenshots/classicwb_adv2.png?raw=true)

![ClassicWB ADV 3](screenshots/classicwb_adv3.png?raw=true)

![ClassicWB ADV 4](screenshots/classicwb_adv4.png?raw=true)

![ClassicWB ADV 5](screenshots/classicwb_adv5.png?raw=true)

![ClassicWB ADV 6](screenshots/classicwb_adv6.png?raw=true)

![ClassicWB ADV 7](screenshots/classicwb_adv7.png?raw=true)

![ClassicWB ADV 8](screenshots/classicwb_adv8.png?raw=true)