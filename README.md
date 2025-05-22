# MSI-Bravo-15-B7ED
Optimize the "Multiple-Serious-Issue" Bravo 15 B7ED

Vietnamese language: coming soon

> [!IMPORTANT]
> I won't responsible if you make any damage on your device while doing every step below.If you point the finger at me for messing up your device, I will laugh at you(really)

## Recommend

1.For AMD cpu and gpu driver, recommend using the one that MSI provided in MSI webside

https://download.msi.com/nb_drivers/vga/AMD_VGA_31.0.22056.8001_31.0.22056.8001_0xe1b39912.zip

If you want use the 3rd party driver,recomend use this:https://rdn-id.com/#compat

2.Disable DXNAVI:

https://github.com/cbk0313/Radeon-DX-Configurator

Download it,open the app and choose "Set regular DX11"

3.Turn On Shader Cache

Go to "Computer\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\Class\{4d36e968-e325-11ce-bfc1-08002be10318}\0000\UMD" in Registry Editor, find Shader cache and set value from 31 to 32

4.Disable Multi-plane Overlay (MPO)

"HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\Dwm" and create a DWORD32 VALUE called "OverlayTestMode" and set the value to 5.

Or,dowload mpo_disable.reg in this link and apply

https://nvidia.custhelp.com/app/answers/detail/a_id/5157/~/after-updating-to-nvidia-game-ready-driver-461.09-or-newer%2C-some-desktop-apps

5.Turn off preload page on Chrome,Startup boost in System and performance on MS Edge

6.Turn off Fast Startup

7.Go to BIOS, find Advance => User Scenario and set to Performance mode. (if you reset BIOS, you have to set this again)

8.Disable ULPS 

Go to Registry Editor, ctrl f the "EnableUlps" and set EnableUlps and EnableUlps_NA (both gpu) to " 0 "

## Optional

9.If you reinstall Windows, you can install Win 10 iot LTSC or if you want Win 11 install Win 11 23H2 Enterprise or Win 11 iot LTSC

10.Using Chris Titus Tech's Windows Utility

11.Update BIOS (not recommend,really), reset BIOS (just in case)

12.If you don't want use MSI Center, using YAMDCC (Yet Another MSI (Dragon) center Clone) instead 

https://github.com/Sparronator9999/YAMDCC

13.Repaste the thermal paste,find a laptop stand or laptop cooling pad (Recommend)

Note: For step 2,3,4,8 if you reinstall or update AMD driver (just in case), you have to repeat the all the step again.

Will update more soon.


