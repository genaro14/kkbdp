# KKBDP
## Kiss Keyboard Project
+ clone like this:  
´´´bash
 $ git clone --recurse-submodules -j8 https://github.com/genaro14/kkbdp
´´´
Uploading the CONTRA Firmware, asuming that Repo was clone to home folder
´´´bash
$ ~/.arduino15/packages/arduino/tools/avrdude/6.3.0-arduino17/bin/avrdude -C~/.arduino15/packages/arduino/tools/avrdude/6.3.0-arduino17/etc/avrdude.conf -v -patmega32u4 -cavr109 -P/dev/ttyACM0 -b57600 -D -Uflash:w:~/keyboard/tmk_keyboard/keyboard/contra/contra.hex:i
´´´


## Tool
+ Tutorial Kicad: https://github.com/ruiqimao/keyboard-pcb-guide#setting-up
+ Layout Editor: http://www.keyboard-layout-editor.com
+ Plate: http://builder.swillkb.com/
+ Case: https://www.thingiverse.com/thing:4402730
+ Firmware: https://github.com/qmk/qmk_firmware/tree/master/keyboards/planck


### Contra:
http://www.40percent.club/2018/03/contra.html
### Contra Plates
https://github.com/ai03-2725/ContraPlates

### Objective 1: 40% Ortholinear
+ Include as much Open Source environment as possible.
+ Single sided PCB(ultra low cost, etching at home possible)
+ Cherry Mx(or clones) only
+ Standard THT diodes
+ Arduino Pro micro(for availability)
+ Kicad Desing


Status:
Seems posibble
