# Octopus MAX EZ

## Motors
| Name | Type |	EN | STEP |	DIR | CS | Voltage | Driver |
|:---:|------|----|------|-----|----|---- |---- |
| 1 | X | PE6  | PC13 | PC14 | PG14 | 48V | 5160 |
| 2 | X1 | PE3 | PE4 | PE5 | PG13 | 48V | 5160 |
| 3 | Y | PE2 | PE1 | PE0 |	PG12 | 48V | 5160 |
| 4 | Y1 | PB7 | PB8 | PB9|	PG11 | 48V | 5160 |
| 5 | Z | PB6 | PB5 | PB4 | PG10| 24V | 2209 |
| 6 | Z1 | PD5| PG15 | PB3 | PG9| 24V | 2209 |
| 7 | Z2 | PD4 | PD3 |	PD2	| PD7| 24V | 2209 |
| 8 | Extruder | PA15 | PA10 |	PA9 | PD6| 24V | 2209 |

## Fans 2 pin
| Name | Type |	Ground| Voltage |
|:---:|---|:---:|:---:| 
|0|	Hotend | PA6| 12V |
|1| |	PA5| |
|2|	Case |	PA4| 12V |
|3|	Case |	PA3| 12V |
|MFAN| | VF6 | Shares Fan6!|


## Fans 4 pin
| Name | Type |	Tach | PWM | Voltage |
|:---:|---|:---:|:---:|:---:|
|4|	Part Cooling |	PC3| PA1 | 12V |
|5|	|	PC1| PF8 | |
|6|	|	PC2| PA2 | | 

## Temperature
| Name | Type |	Pinout|
|:---:|---|:---:| 
|THB|	Bed Temp |	PB1|
|TH0|	Hotend|	PB0|
|TH1|	|	PC5|
|TH2|	|	PC4|
|TH3| Chamber	| PA7|

## Endstop
| Name | Type |	Pinout|
|:---:|---|:---:| 
|MIN1| | PF0|
|MIN2| | PF2|
|MIN3| | PF4|
|MIN4| | PF3|
|MIN5| | PF1|
|MIN6| | PC15|

## RGB
| Name | Type |	Pinout|
|:---:|---|:---:| 
|RGB1| | PE10|
|RGB2| | PE9|

## Probe
| Name | Type |	Pinout| |
|:---:|---|:---:|:---:| 
|Probe| | PB14| PB15|