# DWIN MODBUS MASTER

## Edit file "22_Config.bin" (file in DWIN_SET folder) with HxD program. Set variables, start at 0001C000 (next 0001C010)

## D0 => activate request
## D1 => slave ID
## D2 => slave function
## D3 => slave total number of registers requested
## D4 => slave timeout
## D5 => mode (0x00 unconditional mode, 0x01 conditional mode, do for D6 and D7)
## D6 => settings (0x00 not active, 0x01 page number)
## D7 => settings (0x00 not active, 0x01 page number)
## D8 => display number of register
## D9 => display number of register
## DA => slave number of register
## DB => slave number of register
## DC => none
## DD => none
## DE => none
## DF => none