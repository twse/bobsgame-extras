﻿# Extra stuff for bob's game
Contains extra stuff for bob's game excluding fonts.

## Google search form (requires internet connection)
The form is not present in the [Bob Corporation website](http://www.bobcorporation.com/). Includes an option to search the Fandom wiki created in 2009. The option to search the forum is not included (all forums are private; it runs a version of XenForo from 2016). The logo is available in PNG or SVG.

## Art Department
Want to be a show-off? Impress your friends? This is the place. Robert Pelloni offers a few wallpapers for you. In any case, please feel free to download these and use them on your desktop.

### Icons
Icons in OS/2 format based on the lowercase letters of [bob's game font](http://www.bobcorporation.com/fonts/bobsgame.ttf) for use with OS/2 programs. Use them to replace icons from the program resources. See **Third-Party Notices.md** for commercial and unsupported freeware credits.

### Nintendo 3DS Skin
Use theme managers (Anemone, CHMM, Themely, ThemePack, etc. etc. etc.) to replace the skin. The skin was created with 3DS Theme Editor.

### Windows User Account Picture
Use this to replace the user account picture (this can be done in Windows XP via **Control Panel: User Accounts: Change your picture** (category view) or **Control Panel: User Accounts: Your username: Change my picture** (classic view) or in Windows Vista and 7 via **Control Panel: User Accounts and Family Safety: User Accounts: Change your picture** (category view) or **User Accounts: Change your picture** (normal view) or in Windows 8 via **Start: Your username: Change account picture** or **PC settings: Personalize: Account picture: Browse** or in Windows 10 via **Settings: Accounts: Your account: Your picture: Browse**). The default pictures are located in Windows XP at `Documents and Settings\All Users\Application Data\Microsoft\User Account Pictures\Default Pictures` (Images should be 48×48) or in Windows Vista and 7 at `ProgramData\Microsoft\User Account Pictures\Default Pictures` (Images should be 128×128).

### Windows Desktop Theme
Use this to replace the desktop theme in Windows. Includes Windows Aero effects if Windows Vista or 7 is running.

### ReactOS Logon GINA Header
Use this to replace the first bitmap resource in `msgina.dll`. **Nimbus Sans Mono** is used to display the modified image. (This font is copyrighted by URW++.)

## Sound Scheme
Use this to replace system sounds or change it through the sound settings (e.g. in **Control Panel** in Windows, **System Setup** in OS/2 or **Preferences** in BeOS or Haiku, it is located under **Desktop Themes: Settings: Sound events** or **Sounds and Multimedia: Sounds: Sound Events** in Windows 95/98/ME, **Sounds** in Windows 2000, BeOS or Haiku, **Sounds and Audio Devices** in Windows XP (also in **Sounds, Speech, and Audio Devices** in category view), and under **Sound: Sounds: Program Events** (also in **Hardware and Sound** in category view or **Personalization** in icon view) in Windows Vista & above, OS/2 and more, **Sound and Audio Devices** on ReactOS, and **Settings: Personalization: Themes: Sounds** in Windows 10). The sound scheme was created with Windows Sound Recorder (Windows XP version) and Wavosaur. Under Windows, the sounds have to be copied to `%SystemRoot%\media`.

Windows 95 until 7 allows changing the login/logoff/shutdown sounds (with Windows 8 & above, the `ExcludeFromCPL` value was added to `WindowsLogoff` and `WindowsLogon` sound events; remove this value to show these events).

### Index of sound events
| Windows name                  | OS/2 name                 | Filename                    |
|-------------------------------|---------------------------|-----------------------------|
| None                          | Alarm Clock               | TBD                         |
| Asterisk                      | None                      | BG Balloon.wav              |
| None                          | Begin drag                | TBD                         |
| Blocked Pop-up Window         | None                      | BG Notify.wav               |
| Calendar Reminder             | None                      | BG Notify.wav               |
| Change Theme                  | None                      | TBD                         |
| Close Program                 | Closing window (Animated) | BG Close Program.wav        |
| Complete Navigation           | None                      | TBD                         |
| Critical Battery Alarm        | None                      | BG Battery Critical.wav     |
| Critical Stop                 | Error                     | BG Critical Stop.wav        |
| Default Beep                  | Error                     | BG Error.wav                |
| Desktop Mail Notification     | None                      | BG Notify.wav               |
| Device Connect                | None                      | BG Hardware Insert.wav      |
| Device Disconnect             | None                      | BG Hardware Remove.wav      |
| Device Failed to Connect      | None                      | BG Hardware Fail.wav        |
| Empty Recycle Bin             | Recycle                   | BG Recycle.wav              |
| None                          | End drag                  | TBD                         |
| Exclamation                   | Warning                   | BG Exclamation.wav          |
| Exit Windows                  | System shutdown           | BG Shutdown.wav             |
| Fax error                     | None                      | BG Error.wav                |
| Fax line rings                | None                      | TBD                         |
| Fax sent                      | None                      | TBD                         |
| Feed Discovered               | None                      | TBD                         |
| Information                   | Information               | BG Information Bar.wav      |
| Instant Message Notification  | None                      | BG Notify.wav               |
| Low Battery Alarm             | None                      | BG Battery Low.wav          |
| Maximize                      | None                      | BG Maximize.wav             |
| Menu Command                  | None                      | TBD                         |
| Menu Pop-up                   | None                      | TBD                         |
| Message Badge                 | None                      | BG Notify.wav               |
| Minimize                      | None                      | BG Minimize.wav             |
| Move Menu Item                | None                      | TBD                         |
| New Fax Notification          | None                      | BG Notify.wav               |
| New Mail Notification         | None                      | BG Notify.wav               |
| New Text Message Notification | None                      | BG Notify.wav               |
| NFIP Completion               | None                      | BG Notify.wav               |
| NFIP Connection               | None                      | BG Hardware Insert.wav      |
| Notification                  | None                      | BG Notify.wav               |
| Notification Bar              | None                      | BG Notify.wav               |
| Open Program                  | Opening window (Animated) | BG Open Program.wav         |
| Print Complete                | None                      | BG Notify.wav               |
| None                          | Printer error             | BG Error.wav                |
| Program Error                 | Error                     | BG Error.wav                |
| Question                      | Information               | BG Notify.wav               |
| Restore Down                  | None                      | BG Minimize.wav             |
| Restore Up                    | None                      | BG Maximize.wav             |
| Search Provider Discovered    | None                      | TBD                         |
| Select                        | None                      | BG Select.wav               |
| Show Toolbar Band             | None                      | TBD                         |
| Start Navigation              | None                      | TBD                         |
| Start Windows                 | System startup            | BG Startup.wav              |
| System Notification           | Information               | BG Information.wav          |
| Windows Logoff                | System shutdown           | BG Shutdown.wav             |
| Windows Logon                 | System startup            | BG Startup.wav              |
| Windows User Account Control  | None                      | BG User Account Control.wav |

## Windows OEM Branding
The zipped archive is included for use with Windows 95 until XP.

For users running Windows Vista & above, the registry keys are located in HKLM on `OEMInformation` by adding the following keys:
* **Logo**: `OEMlogo.bmp`
* **Manufacturer**: Robert Matthew Pelloni
* **SupportURL**: Second line in the `Support Information` heading in `OEMinfo.ini`

## Boot Skin (Windows 9x and ME)
Available in CS, DA, DE, EN, ES, FI, FR, HU, IT, KO, NL, PL, PT-BR, RU and TR. Rename `bobsgame.bmp` to `logo.sys` (copied to the root drive top level directory), `shutdown.bmp` to `logow.sys` and `safetopoweroff.bmp` to `logos.sys` (copied to the Windows directory).

**Note:** Windows 9x or ME must be in VGA to display the startup or shutdown screens (EGA only shows the textual output).

## Boot Skin (Windows XP)
For use with the Windows XP version of [BootSkin](https://www.stardock.com/products/bootskin/) only. Available in DE, EN, ES, FR, IT, JA, KO, NL, PL, RO, RU, SV and TR. Attempting to install with the Windows Vista version will most likely fail, so please don't try it. I created this with Windows Paint.

## Palm OS Emulator Skin
Use this to replace the Generic skin from the executable file (bmp) or simply access them from the Skins dialog (jpg). The skin is assigned to some Palm devices. The jpg files were created with [PMView](https://www.pmview.com/).

This skin can be used with the emulators listed below. Robert Pelloni is not the original author of these emulators. The original copyright notice and the license and contributor list is set forth below. Robert Pelloni licenses these emulators to you under the terms set forth in the BobCorporation license agreement (available in BSD-style). Robert Pelloni reserves all rights not expressly granted under this agreement, whether by implication, estoppel or otherwise.

### Palm Hardware Emulator
Copyright © 2013-2014 Perpendox Software LLC

This software is paid from the [Google Play Store](https://play.google.com/store/apps/details?id=com.perpendox.phem). The company released the source code using the same license in Palm OS Emulator (see below) but the Perpendox Software website was taken down.

### Palm OS Emulator
Copyright © 1998-2002 Palm, Inc.

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see .

#### Contributors
* Steve Achelis
* Kenneth Albanowski
* Pedro Alves
* Vladimir Amarante
* Chris Antos
* Akhil Arora
* Bruce Ashley – Skins
* Jon Aslund
* Andrew Ball
* Mark Baysinger
* Chunk Bazil
* Stephen Best
* Harini Bharadvaj
* Tom Bulatewicz
* Peter Burka
* Mike Chen
* Eugene Chin
* Tilo Christ
* Justin Clark
* Toshi Clark
* Ben Combee
* Radu Cornea
* Mark Corry
* Jonathan Cox
* Carlton Craighead
* David Creemer
* Art Dahm
* Ben Darnell – Debian packaging
* John C. Daub
* Michael S. Davis
* David A. Desrosiers
* Sushama Dharmadhikari
* Adam Dingle
* Matt Disher
* Ivan Doitchinov
* Harry Dolan
* Jesse Donaldson
* Bert Driehuis
* Paul Dugas
* John Duhart
* Red Dutta
* Bob Ebert
* Stuart Eichert
* Brian Estes
* Dan Fahrion
* Christian Falch
* David Fedor
* Alan Finke
* Anthony Fishbeck
* Ron Flax
* Roger Flores
* Jon Fo
* Jean-loup Gailly – Principal author of zlib
* Gregory Allen Gaub
* Michael Glickman
* Gary Gorsline
* Scott Gruby – Carbon port
* Michael Hado
* Adam Hampson
* Ken Hancock
* Steve Haneman
* Guilherme C. Hazan
* Greg Hewgill – Original author
* Stephen P. Hill
* Horace Ho
* Stefan Hoffmeister
* Chad House
* Eric House
* Christopher Hunt
* Andy Ihlenfeldt
* David A. Jablonski
* Thomas Hagen Johansen
* Dave Johnson
* Derek Johnson
* Scott Johnson
* Michael R. Kedl
* David Kendall
* John Kinast
* Oliver King-Smith
* Bill Kirby
* Jerry L. Kirk
* Holger Klawitter
* Martin Kobold
* Darren Kropp
* Ken Krugler
* Vitaly Kruglikov
* Yoshiyuki Kubo
* Waddah Kudaimi
* Ron Kupke
* Steve Lemke
* B. Cameron Lesiuk
* Rob Leslie
* Peter N Lewis
* Jerry Lin
* Andreas Linke
* Adam Liss
* John Ludwig – FreeBSD packaging
* Mark Lussier
* Kelly Maher
* Stuart Malone
* Bob Marcum
* Ron Marianetti
* John Marshall
* Brian Mathis
* Scott Maxwell
* Daniel McCarthy
* Mike McCollister
* Maurizio Moretti
* Doug Morrison
* Hal Mueller
* Mike Nagy
* Matthias Ulrich Neeracher
* Paul Nevai
* Regis Nicolas
* Michael Nordstrom
* Hiroyuki Okamoto
* Eskil Heyn Olsen
* Mark Ordal
* Frederic Paolucci
* Alexandre Parenteau
* Gavin Peacock
* Mark Peters
* Bob Petersen
* James Phillips
* Florent Pillet
* Bill Pittore
* Dan Poirier
* Patrick Porlan
* Jeff Prosise
* Mike Puckett
* Jameson Quinn
* Quinn "The Eskimo!"
* Neil Rhodes
* Rick Richardson
* Chris Ridd
* Ryan Robertson
* Alex Robinson
* Keith Rollin
* Dan Rowley
* Markus Schmid
* Bernd Schmidt – Amiga port
* Craig Schofield – macOS port
* Ben Sessoms
* Douglas R. Shefsky
* Flash Sheridan
* Phil Shoemaker
* Paul Silagi
* Greg Simon
* Jason Simpkins
* David Slotter
* Dan Smith
* Bill Spitzak
* Mahendra Tailor
* Arturo Tena
* Ben Thomas
* Mike Turcotte
* David Vaportrails
* Rick Wagner
* Mike Walter
* Marq Watkin – Pandora build
* William F. Weiher III
* Catherine White
* Tim Wiegman
* Ben Williamson
* Keith Wolcott
* Jeff Yasuda
* Frank Yellin
* Richard Ziegelmaier
