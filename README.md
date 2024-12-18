## What is UnofficialOSAddOns?

UnofficialOSAddOns is a simple tool that was forked from [Portmaster](https://github.com/christianhaitian/PortMaster) created by [Christian Haitian](https://github.com/christianhaitian)

This tool allows you to download various game ports that are not available in Portmaster. This will require the latest Portmaster to run correctly, which should already be installed in UnofficialOS. 

One of the goals of UnofficialOSAddOns is to not install or upgrade any existing OS libraries for any ports.  Any of the ports that need a particular non standard library are maintained within the ports' folder and made available specifically to that port during execution.

Most of the the ports available through JelosAddOns have only been configured to launch on the Anbernic RG552 running the latest version of UnofficialOS.

All ports in UnofficialOSAddOns should follow the same formating as Portmaster.

## Install info

UnofficialOSAddOns should come preloaded on the latest version of UnofficialOS

You can find the latest details on how to install UnofficialOS [here](http://unofficialos.org/)

## Do I have to use UnofficialOSAddOns to install ports?

No.  You can simply go to the UnofficialOSAddOns repo (https://github.com/RetroGFX/UnofficialOSAddOns), find the .zip of the port you want, download it and unzip the contents of it to the /roms/ports folder.  You'll also need to copy the UnofficialOSAddOns folder and Portmaster foldeer to your /roms/ports folder.

## How do I get more info about the ports in this repo like the sources used and additional asset needs if applicable?

wiki to come soon

## If there are updates to Ports, how will that work?

Just run UnofficialOSAddOns and reinstall the port.  You can also unzip the associated .zip for the port you want and unzip the contents of it to the ports folder.  This should install the latest port related files if they've been updated in UnofficialOSAddOns.  In most cases, it should not impact any existing game data you had to provide or existing saves unless the updated port made changes to the port backend that impacts previous saves.
