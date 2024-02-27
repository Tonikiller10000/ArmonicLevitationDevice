# ArmonicLevitationDevice

## Description:
This device uses 40Khz sound wave frequencies to levitate small objects. It uses an smd NE555 to generate a 40KHz square wave signal witch is transformed in a 40KHz sine wave signal with an 


<table>
  <tr>
    <td>

### Pinout
- EEPROM Data pins
    - D0-D7     : Data EEPROM IO pins
- Shift Register control pins
    - CLK       : Shift Register CLK pin
    - LATCH     : Shift Register Latch pin
    - OE        : Shift Register OE pin
    - DataIn    : Shift Register Serial Data In pin
- EEPROM control pins
    - WE        : EEPROM Write Enable pin
    - OE        : EEPROM Output Enable pin
    - GND       : arduino GND
    - VCC       : arduino 5V
    </td>
    <td><img src="https://github.com/Tonikiller10000/EEPROM_PROGRAMER/blob/main/EEPROM_PROGRAMER_V2.0/EEPROM_PROGRAMER_V2.0_Pictures/EE2.jpg" width=300 height=400 ></td>
  </tr>
</table>


### Version V3.0
This design is an plug and play version. It is an arduino shield, with some extra power, pins and 4 smd dip switches with one power switch and 8 modes to program the eeprom on the go, without the need of an computer.
<table>
  <tr>
    <td><img src="https://github.com/Tonikiller10000/EEPROM_PROGRAMER/blob/main/EEPROM_PROGRAMER_V3.0/EEPROM_PROGRAMER_V3.0_Pictures/ee32.png" width=300 height=200 ></td>
    <td><img src="https://github.com/Tonikiller10000/EEPROM_PROGRAMER/blob/main/EEPROM_PROGRAMER_V3.0/EEPROM_PROGRAMER_V3.0_Pictures/ee31.png" width=300 height=200 ></td>
    <td><img src="https://github.com/Tonikiller10000/EEPROM_PROGRAMER/blob/main/EEPROM_PROGRAMER_V3.0/EEPROM_PROGRAMER_V3.0_Pictures/ee33.png" width=300 height=200 ></td>
  </tr>
</table>

## Links:
74HC595 datasheet (shift register): https://datasheetspdf.com/pdf-file/446162/ONSemiconductor/74HC595/1
