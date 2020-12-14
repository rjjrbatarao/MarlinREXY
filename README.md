# MarlinREXY
Quick modification of marlin to support remote direct drive belt drive extrusion.

## Disclaimer
This is untested and I never verified the changes if its correct and satisfies the operation of the remote extruder.
Flash at your own risk. Im not responsible if it destroys your board and or it causes injuries, permanent damage to your printer, home and properties.

# Description
As you can see below remote extruder belt drive can be achieved using markforged kinematics on Extruder motor relative to Y axis movement. I just copied the newly merged markforge kinematics codes and changed it to work with extruder motion relative to y motion theoretically.
You can find the newly added kinematics in Configuration.h as HYBRID_E, note my naming is randomly picked and i might think of other proper name in the future. This only works with corexy setup and is untested. Bug fixes/Contributions are welcomed.

# Layout
![layout](https://github.com/rjjrbatarao/MarlinREXY/blob/main/layout.jpg)
