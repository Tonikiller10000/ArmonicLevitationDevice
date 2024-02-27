# ArmonicLevitationDevice

## Description:
This device uses 40Khz sound wave frequencies to levitate small objects. 
It uses an smd NE555 to generate a 40KHz square wave signal witch is transformed in a 40KHz sine wave signal with an TC78H621FNG Dual-Bridge driver.

<table>
  <tr>
    <td><img src="https://github.com/Tonikiller10000/ArmonicLevitationDevice/blob/main/LevitationPictures/47.png" ></td>
    <td><img src="https://github.com/Tonikiller10000/ArmonicLevitationDevice/blob/main/LevitationPictures/44.png" ></td>
    <td><img src="https://github.com/Tonikiller10000/ArmonicLevitationDevice/blob/main/LevitationPictures/43.png" ></td>
  </tr>
</table>

### Schematic:
<img src="https://github.com/Tonikiller10000/ArmonicLevitationDevice/blob/main/LevitationPictures/45.png" >




## How/where to use:

<table>
  <tr>
    <td> 
        It can be powered with a 9V battery. (5-15v operating voltage range)
        Because of it`s design, multiple tipes of transmiters/transducers can be used by bending the pins. 
        To use it, you can use only one board/transmitter ans a close flat surface to reflect the wave. 
        For a stronger hold, you can use another transmitter connected to the SP2 pins.
   </td>
    <td><img src="https://github.com/Tonikiller10000/ArmonicLevitationDevice/blob/main/LevitationPictures/p1.webp" width= 600></td>
  </tr>
</table>

> [!IMPORTANT]
> Change the distance between the transmitter1 and the surface/transmitter2 to create the nodes and antinodes for the project to work.

<table>
  <tr>
    <td> 
    This king of technology, can be used in medical industry to observe and experiment with liquids without making contact with them.</td>
    <td><img src="https://github.com/Tonikiller10000/ArmonicLevitationDevice/blob/main/LevitationPictures/p2.png" width= 400></td>
  </tr>
</table>



## Links:
- TC78H621FNG datasheet (Dual-Bridge driver): https://toshiba.semicon-storage.com/info/TC78H621FNG_datasheet_en_20170410.pdf?did=57992&prodName=TC78H621FNG
- 78L05 datasheet (voltage regulator): https://www.sparkfun.com/datasheets/Components/LM7805.pdf
- NE555 datasheet (timer): https://pdf1.alldatasheet.com/datasheet-pdf/view/17972/PHILIPS/NE555.html
- Ultrasonic transducer: https://www.murata.com/-/media/webrenewal/products/sensor/ultrasonic/open/datasheet_maopn.ashx
- general transducers: https://tecsho.com/Download/Download/126816/fp