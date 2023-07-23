# Open EV2400 
![Static Badge](https://img.shields.io/badge/license-GPL--3.0-orange)

## Safety statement

![warning](https://github.com/IRDecoyFlare/OpenEV2400/blob/main/Picture/warning.png)

This project may contains high voltage,high temperature and other hazard elements. Readers should undersatnd these risks and take proper actions to pervent being injured. 

## Introduction

The [EV2400](https://www.ti.com/tool/EV2400) is a toolset for programming and debug BQ series devices manufactured by Texas Instruments. The EV2400 is the EV2300's successor. Compared to the EV2300, the EV2400 has higher compatibility with newer systems and chips. Several designs are  available in the lib:

- **EV2400 Original** _[most similar to TI's EV2400-EVM]_(Figure.1)

- **EV2400 Low Cost** (Figure.2)

- **EV2400 Inexpensive** (Figure.3)

- **EV2400 Affordable** _[A CRAZY THING available for purchase on TaoBao]_(Figure.4)


#### Differences

Spec | EV2400 Original  |EV2400 Low Cost|EV2400 Inexpensive|EV2400 Affordable
:----: | :----: |:----: |:----: |:----:
Isolated USB port |yes|no|no|no
I/O protection  | yes |yes|no|yes
Upgrade from TI|yes|yes|yes|unknown
MCU MSP430|F5529|F5529|F5529|F5528
Verified |yes|yes|yes|no

On the user level there is no difference in handling or operation between these different revisions.

### Pictures
![Figure.1](https://github.com/IRDecoyFlare/OpenEV2400/blob/main/Picture/Figure1.png)
Figure.1

![Figure.2](https://github.com/IRDecoyFlare/OpenEV2400/blob/main/Picture/Figure2.png)
Figure.2

![Figure.3](https://github.com/IRDecoyFlare/OpenEV2400/blob/main/Picture/Figure3.png)
Figure.3

![Figure.4](https://github.com/IRDecoyFlare/OpenEV2400/blob/main/Picture/Figure4.png)
Figure.4

### Pin Configurations

Offical EV2400 pin configurations(Figure.5)
![Figure.5](https://github.com/IRDecoyFlare/OpenEV2400/blob/main/Picture/Figure5.png)
Figure.5

Open EV2400 pin configurations(Figure.6)
![Figure.6](https://github.com/IRDecoyFlare/OpenEV2400/blob/main/Picture/Figure6.png)
Figure.6

### Firmware
Unfortunately,TI doesn't make the code public. But we find the frimware extracted from the offical EV2400 on a Chinese website. [link](https://download.csdn.net/download/qq_38662273/85409591?utm_source=bbsseo) 
Please use [UNIFLASH](https://www.ti.com/tool/UNIFLASH) , or other software with EZFET burning. Firmware is divided into 2 different types with the same function and no difference. 

### PCB files 
 PCB is designed by EasyEDA Pro .All files are provided(including pcb files and Schematic)