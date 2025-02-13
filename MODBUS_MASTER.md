# DWIN MODBUS MASTER

## Edit file "22_Config.bin" (file in DWIN_SET folder) with HxD program. Set variables, start at 0001C000 (next 0001C010)

## D0 => activate request <=> (5A)
## D1 => slave ID <=> (example: 01)
## D2 => slave function <=> (example: 03)
## D3 => slave total number of registers requested <=> (example: 01)
## D4 => slave timeout <=> (example: 30)
## D5 => mode (0x00 unconditional mode, 0x01 do for D6 and D7) <=> (example: 01)
## D6 => settings (0x00 not active, 0x01 page number) <=> (example: 00)
## D7 => settings (0x00 not active, 0x01 page number) <=> (example: 00)
## D8 => display number of register <=> (example: 10)
## D9 => display number of register <=> (example: 00)
## DA => slave number of register <=> (example: 00)
## DB => slave number of register <=> (example: 00)
## DC => none
## DD => none
## DE => none
## DF => none
