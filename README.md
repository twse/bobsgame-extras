# bob's game extra stuff
Contains extra stuff for bob's game except fonts.

## Art Department
Want to be a show-off? Impress your friends? This is the place. Robert Matthew Pelloni will be offering a wallpaper for you. In any case, please feel free to use them on your desktop.

### Icons
Icons in OS/2 format based on the lowercase letters included in the bob's game font for use with OS/2 programs. Use them to replace icons from the program resources. See **Third-Party Notices.md** for commercial and unsupported freeware credits. See **Legal Notices.md** in each software category folder for brief legal notices.

### Nintendo 3DS Skin
Use theme managers ([Anemone](https://github.com/astronautlevel2/Anemone3DS), [CHMM2](https://github.com/Rinnegatamante/CHMM2), [Themely](https://github.com/Ann0ying/Themely), etc. etc. etc.) to replace the skin. The skin was created with [3DS Theme Editor](https://github.com/usagirei/3DS-Theme-Editor).

### Windows User Account Picture (BMP)
Use this to replace the user account picture (this can be done in Windows XP via **Control Panel: User Accounts: Change your picture** (category view) or **Control Panel: User Accounts: Your username: Change my picture** (classic view) or in Windows Vista and 7 via **Control Panel: User Accounts and Family Safety: User Accounts: Change your picture** (category view) or **User Accounts: Change your picture** (normal view) or in Windows 8 via **Start: Your username: Change account picture** or **PC settings: Personalize: Account picture: Browse** or in Windows 10 and 11 via **Settings: Accounts: Your account: Your picture: Browse**).

**Default user account picture locations**
* Windows XP: `Documents and Settings\All Users\Application Data\Microsoft\User Account Pictures\Default Pictures` (Images should be 48×48 and are available as bmp)
* Windows Vista, 7, 8, 10 and 11: `ProgramData\Microsoft\User Account Pictures\Default Pictures` (Images should be 128×128 in Windows Vista and 7 and are available as bmp. Images are available in 32×32 up to 448×448 and in bmp or png in Windows 8, 10 and 11).

### Windows Desktop Theme
Use this to replace the desktop theme in Windows. Includes Windows Aero effects if Windows Vista or 7 is running.

### ReactOS GINA Logon Header
Use this to replace the first bitmap resource in `msgina.dll`. The image is typeset in Nimbus Sans Mono (designed by URW Type Foundry), available for purchase through MyFonts.

## Sound Scheme
Use this to replace system sounds or change it through the sound settings (e.g. in **Control Panel** in Windows, **System Setup** in OS/2 or **Preferences** in BeOS/Haiku, it is located under **Desktop Themes: Settings: Sound events** or **Sounds and Multimedia: Sounds: Sound Events** in Windows 95/98/ME, **Sounds** in Windows 2000, BeOS/Haiku, **Sounds and Audio Devices** in Windows XP (also in **Sounds, Speech, and Audio Devices** in category view), and under **Sound: Sounds: Program Events** (also in **Hardware and Sound** in category view or **Personalization** in icon view) in Windows Vista & above, OS/2 and more, **Sound and Audio Devices** on ReactOS, and **Settings: Personalization: Themes: Sounds** in Windows 10 and 11). Under Windows, the sounds have to be copied to `%SystemRoot%\media` or `%windir%\media` (make sure you're logged in as an administrator).

Windows 95 until 7 allows changing the login/logoff/shutdown sounds (with Windows 8 & above, the `ExcludeFromCPL` value was added to `WindowsLogoff` and `WindowsLogon` sound events; remove this value to show these events).

> [!NOTE]
> The sound scheme was created and edited with Sound Recorder (Windows XP) and [Wavosaur](https://www.wavosaur.com/).

### Index of sound events
| Windows name                  | OS/2 name                 | Filename                    |
|-------------------------------|---------------------------|-----------------------------|
| None                          | Alarm Clock               | BG Alarm.wav                |
| Asterisk                      | None                      | BG Balloon.wav              |
| None                          | Begin drag                | BG Select.wav               |
| Blocked Pop-up Window         | None                      | BG Notify.wav               |
| Calendar Reminder             | None                      | BG Alarm.wav                |
| Change Theme                  | None                      | BG Startup.wav              |
| Close Program                 | Closing window (Animated) | BG Close Program.wav        |
| Complete Navigation           | None                      | BG Notify.wav               |
| Critical Battery Alarm        | None                      | BG Battery Critical.wav     |
| Critical Stop                 | Error                     | BG Critical Stop.wav        |
| Default Beep                  | Error                     | BG Error.wav                |
| Desktop Mail Notification     | None                      | BG Notify.wav               |
| Device Connect                | None                      | BG Hardware Insert.wav      |
| Device Disconnect             | None                      | BG Hardware Remove.wav      |
| Device Failed to Connect      | None                      | BG Hardware Fail.wav        |
| Empty Recycle Bin             | Recycle                   | BG Recycle.wav              |
| None                          | End drag                  | BG Select.wav               |
| Exclamation                   | Warning                   | BG Exclamation.wav          |
| Exit Windows                  | System shutdown           | BG Shutdown.wav             |
| Fax error                     | None                      | BG Error.wav                |
| Fax line rings                | None                      | BG Notify.wav               |
| Fax sent                      | None                      | BG Alarm.wav                |
| Feed Discovered               | None                      | BG Alarm.wav                |
| Information                   | Information               | BG Information Bar.wav      |
| Instant Message Notification  | None                      | BG Alarm.wav                |
| Low Battery Alarm             | None                      | BG Battery Low.wav          |
| Maximize                      | None                      | BG Maximize.wav             |
| Menu Command                  | None                      | BG Select.wav               |
| Menu Pop-up                   | None                      | BG Select.wav               |
| Message Badge                 | None                      | BG Alarm.wav                |
| Minimize                      | None                      | BG Minimize.wav             |
| Move Menu Item                | None                      | BG Select.wav               |
| New Fax Notification          | None                      | BG Alarm.wav                |
| New Mail Notification         | None                      | BG Alarm.wav                |
| New Text Message Notification | None                      | BG Alarm.wav                |
| NFIP Completion               | None                      | BG Alarm.wav                |
| NFIP Connection               | None                      | BG Hardware Insert.wav      |
| Notification                  | None                      | BG Notify.wav               |
| Notification Bar              | None                      | BG Notify.wav               |
| Open Program                  | Opening window (Animated) | BG Open Program.wav         |
| Print Complete                | None                      | BG Alarm.wav                |
| None                          | Printer error             | BG Error.wav                |
| Program Error                 | Error                     | BG Error.wav                |
| Question                      | Information               | BG Notify.wav               |
| Restore Down                  | None                      | BG Minimize.wav             |
| Restore Up                    | None                      | BG Maximize.wav             |
| Search Provider Discovered    | None                      | BG Alarm.wav                |
| Select                        | None                      | BG Select.wav               |
| Show Toolbar Band             | None                      | BG Select.wav               |
| Start Navigation              | None                      | BG Select.wav               |
| Start Windows                 | System startup            | BG Startup.wav              |
| System Notification           | Information               | BG Information.wav          |
| Windows Logoff                | System shutdown           | BG Shutdown.wav             |
| Windows Logon                 | System startup            | BG Startup.wav              |
| Windows User Account Control  | None                      | BG User Account Control.wav |

## Windows OEM Branding
The zipped archive is included for use with Windows 95 until XP.

In Windows Vista & above, the registry keys are located in `HKLM\Software\Microsoft\Windows NT\CurrentVersion\OEMInformation` (on non-OEM copies, there are no values included within this key) - add the following string values to this key:
* **Logo**: `OEMlogo.bmp`
* **Manufacturer**: Robert Matthew Pelloni
* **SupportURL**: Second line in the `Support Information` heading in `OEMinfo.ini`

## Boot Skin (Windows 9x/ME)
The boot skin is available in 15 languages. Rename `bobsgame.bmp` to `logo.sys` (copied to the system drive's root directory), `shutdown.bmp` to `logow.sys` and `safetopoweroff.bmp` to `logos.sys` (copied to the Windows directory).

> [!NOTE]
> Windows 9x/ME needs VGA to display the startup and shutdown screens.

## Boot Skin (Windows XP)
For use with the Windows XP version of [BootSkin](https://www.stardock.com/products/bootskin/) only. The boot skin is available in 14 languages. Attempting to install with the Windows Vista version will most likely fail, so please don't try it. I created this with Windows Paint.

> [!NOTE]
> Remove both the hyphen and language code at the end of the filename.

## Palm OS Emulator Skin
Use this to replace the Generic skin from the executable file or source code (bmp) or simply access them from the Skins dialog (jpg). The skin is assigned to some Palm devices and available in two languages. The jpg files were created with [PMView](https://www.pmview.com/).

This skin can be used with Palm Hardware Emulator (created by Perpendox Software, LLC in 2013; removed from the Google Play Store and ran on Android devices with Froyo and later) and Palm OS Emulator (AKA Copilot).
