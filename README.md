# IDM Activation Script
_________________________________

###   Activation:
_________________________________

 - This script applies the registry lock method to activate the Internet Download Manager (IDM).

 - This method requires Internet at the time of activation.

 - IDM updates can be installed directly without having to activate again.

 - After the activation, if in some cases, the IDM starts to show an activation nag screen, 
   then just run the activation option again.

_________________________________

###   Reset IDM Activation / Trial:
_________________________________

 - The Internet Download Manager provides 30 days trial period, you can use this script to 
   reset this Activation / Trial period whenever you want.
 
 - This option also can be used to restore status if in case the IDM reports a fake serial
   key and other similar errors.

_________________________________

###   OS requirement: Windows 7, 8, 8.1, 10 & 11
_________________________________

##   How to use it?

###   PowerShell

On Windows 10/11, right-click on the windows start menu and select PowerShell or Terminal.

Copy-paste the below code and press enter:

```
iex(irm is.gd/idm_reset)
```
or
```
iwr -useb https://raw.githubusercontent.com/nilay-code/IDM-Activation-Script/main/IAS.ps1 | iex
```

You will see the activation options, and follow onscreen instructions.

That's all.
_________________________________

 - Project is supported only for Windows 7/8/8.1/10/11 and their Server equivalent.

_________________________________

