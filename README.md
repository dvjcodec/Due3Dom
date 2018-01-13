# Due3Dom

Modular 3D printer driver working as a shield for 32-bit ARM based Arduino DUE.

## Features:
* 20A channel for bed heating (20A fuse) with own power socket
* 2x 10A channel for head heating (10A fuse) with own power socket
* up to 6 external A4988 compatible stepstick drivers (more on expansion port); jumper based step switching
* high current connectors for all power and driver sockets
* input for 4 thermistors
* input for 2 thermocouples
* PWM output for 3 fans

## Connections

### Connecting LCD
* EXP1 on DUE3DOM to be connected with EXP2 on SmartController
* EXP2 on DUE3DOM to be connected with EXP1 on SmartController

## Issues

First board revision (A) needs two manual fixes:
* add protection diode for DUE's power in
* add capacitor to RESET

## Firmware

Supported by official firmware:
* [Repetier](https://www.repetier.com/firmware/dev/index.php)
* [Marlin](https://github.com/esenapaj/Marlin)


## Support
* [Official Website [PL]](http://www.due3dom.pl/)
* [Forum thread [PL/EN]](http://www.fabrykator.pl/board/viewtopic.php?f=12&t=201)


## License

[CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)

## Authors

Krzysztof @ Seaside Customs

## Special THNX

This board was designed with huge support form Fabrykator.pl comunity. Special thnx to: Miś, Garreth, mcexperts, PPJ
