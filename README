[Medion 16192 robot vacuum](https://www.medion.com/medionserviceshop/search?sbf=true&sfs=1&msn=50050242+) - IR commands/codes
=============================================

![Image of Medion 16192 robot vacuum](https://media.medion.com/50050242_PIC-Q?impolicy=prod&w=240)
(all image rights reserved to [Medion](https://www.medion.com/))


Below you can find a list of the [NEC](https://techdocs.altium.com/display/FPGA/NEC+Infrared+Transmission+Protocol) (32 bits) IR commands sent by the remote
for the [Medion 16192 vacuum robot](https://www.medion.com/medionserviceshop/search?sbf=true&sfs=1&msn=50050242+). Data was extracted using an IR receiver and ESP8266 running [Tasmota](https://github.com/arendst/Tasmota).


| Button | Protocol | Bits | Data |
|:------:|:--------:|:----:|:----:|
| Up button | NEC | 32 | 0x02AA55AA |
| Left button | NEC| 32 | 0x02AA33CC |
| Right button | NEC | 32 | 0x02AA44BB|
| Down button | NEC | 32 | 0x02AA6699 |
| OK button | NEC | 32 | 0x02AA22DD |
| Hug walls button | NEC | 32 | 0x02AA9966 |
| Return home button | NEC | 32 | 0x02AA8877 |
| Spot cleaning button | NEC | 32 | 0x02AA7788 |


TODO
----
* `PLAN` and `CLOCK` mode: When pressing `PLAN` or `CLOCK`, the remote switches to 48 bit `KELON` protocol (or something that resembles `KELON`). In the data the hour + minutes are encoded. To use these features a formula should be found linking hour + minutes to the data that has to be send over IR.
