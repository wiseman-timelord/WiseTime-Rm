# WiseRain
Status: Working, better than ever, but still possible devlopment.

## DESCRIPTION
Here is the official Wiseman-Timelord RainMeter skin, yes there is one. This skin is a PowerShell focused skin, flashing powershell scripts on a delay, for lower processing, while utilizing "PowershellRM" plugin. Its an advanced custom rain-meter skin based on powershell scripts with all, of the other things in place and done through the use of cmdlets and built-in windows powershell. I associate it with programs like, Task Monitor or Process Hacker, as I would otherwise likely be gaining such info with such a program.

### FEATURES
- ** Dark Theme **: Designed for dark-themed desktops, where the background is dark and the text is light.
- ** User Friendly **: Use of powershell scripts with clearly commented global variables at the top, for customized readings.
- ** Multi-Panel **: Currently has 3 modular panels, System and Network, and the recently enhanced Monitor.
- ** Plugin Enhancement **: Use of "PowershellRM" with, Ps1s and Psd1 (=>v1.02), for enhanced powershell support.
- ** Compatibility **: Supports, IPv4 and truncated IPv6, display of IP address on network panel.
- ** Real-World Units **: Monitoring of, Disk and Network bandwidth usage rate.
- ** Text Graphics **: Monitoring of CPU Usage with text Graphics, example `Usage - 69% - ######     `.

## PREVIEW
- The 3 panels (usb internet, no NIC stat on this occasion)...
<br><img src="./media/wiserain_v116.jpg" align="center" alt="no image">.
- Potential Desktop...
<br><img src="./media/wiserain_desktop_116.jpg" align="center" alt="no image">.

## USAGE
1. Download and Install, the plugin [PowershellRM](https://github.com/khanhas/PowershellRM) into your `Rainmeter/Plugins` folder.
2. Download `WiseRain` from the releases section, to a suitable location.
3. Copy the `WiseRain` folder from the zip into your `RainMeter\Skins` folder.
4. Edit the global variables at the top of the 3 powershell scripts appropriately, to point to the appropriate locations for your setup.
5. Load rain meter or Refresh the skins display, then navigate in the folders in RainMeter, load the 3 panels, system and network and monitor, as you normally would the panels of other skins, you may not always wish to keep the monitor on.   

### NOTATION
- When updating, I suggest deleting the old "WiseRain" folder and replacing with the new, unless its a minor update, in which case replace/over-write.
- If you do not use a Ramdrive, then, change the drive letter and rename the label, to whatever...things should not be left to a dead location.

### REQUIREMENTS
1. [RainMeter](https://www.rainmeter.net/) (to load the skin).
2. Powershell => v3.0.
3. [PowershellRM](https://github.com/khanhas/PowershellRM) (add to `.\Rainmeter\Plugins` folder for the enhanced powershell).

## Development
Here are some possible directions for development...
1. Cpu Usage seems too high, ensure this is the average for all cores, preferably some simple way to gain this; instead of for first cpu or whatever it is doing.
2. Some kind of notation, top 5 important tasks, short note of for example 5 items with editing/input through plugin.
3. A stripped down version of CreditSight in its own panel, with use of additional plugins there will be input box (CreditSight must be completed first).
- DO NOT DO: Top 3 bandwidh using apps, this required special libraries to achieve, at least it was not possible through, cmdlets and .net 4.0.
## DISCLAIMER
This software is subject to the terms in License.Txt, covering usage, distribution, and modifications. For full details on your rights and obligations, refer to License.Txt.
