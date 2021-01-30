set fuses using avrdude
avrdude -p m32u4 -c flip2 -P usb -Ulock:w:0x3F:m -Uefuse:w:0xcb:m -Uhfuse:w:0xd8:m -Ulfuse:w:0xff:m