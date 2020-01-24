# M17_ANL_v2
New M17 hotspot/analyser, this time with ADF7021

## Schematic
Diagram was not tested Yet.

## Technical details

### Most important ICs used in project

* STM32F303CBT6 - MCU which controls data flow, and radio parameters.
* ADF7021 - radio transceiver.

### Testpoints description

| TestPoint NO  | Description | Pin of STM32 | Pin of ADF7021 |
| ------------- | ------------- | ------------- | ------------- |
| TP1  | SPI_SCK  | PB13  | 28 |
| TP2  | SPI_MISO  | PB14  | 27 |
| TP3  | SPI_MOSI  | PB15  | 26 |
| TP4  | SPI_ENABLE  | PA8  | 25 |
| TP5  | RF_ENABLE  | PA9  | 24 |
| TP6  | DClk  | PA6  | 35 |
| TP7  | Data  | PA7  | 34 |
| TP8  | SWD  | PB0  | 33 |
| TP9  | RF_CLK  | PA5  | 36 |
| TP10  | AD  | PA2  | from Filter 1 |
| TP11  | MO  | PA3  | 37 |
| TP12  | DA  | PA4  | to Filter 2 |
| TP13  | FMDM  | to Filter 1  | 33 |
| TP14  | FMM  | from Filter 2  | 21 |


