Added AT+SEND and AT+SENDB commands. Both are <port>:<payload> ; a value of 0 for port uses the application port setting. +SEND accepts a string, +SENDB accepts a hex-encoded binary payload.

Source Code for SN50v3-LB and SN50v3-NB.

SN50v3 uses LA66 module inside. See below for:

# How to Compile Firmware: 
See Step 1 ~ Step 7 of [LA66 Compile Instruction](http://wiki.dragino.com/xwiki/bin/view/Main/User%20Manual%20for%20LoRaWAN%20End%20Nodes/LA66%20LoRaWAN%20Module/Compile%20and%20Upload%20Code%20to%20ASR6601%20Platform/ )

# How to Update Firmware: 
## [via OTA: ](http://wiki.dragino.com/xwiki/bin/view/Main/Firmware%20OTA%20Update%20for%20Sensors/ )
## [via UART ](http://wiki.dragino.com/xwiki/bin/view/Main/UART%20Access%20for%20LoRa%20ST%20v4%20base%20model/ )

