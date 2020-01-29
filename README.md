CCLoader
========

Burn CC25xx firmware using an NodeMCU board.

1. Load the CCLoader Arduino sketch to the MCU board.
2. Wire the pins:

DD (DEBUG_DATA Pin 8) to GPIO14 (D5 on NodeMCU/WeMos D1 Mini) <br>
DC (DEBUG_CLOCK Pin 7) to GPIO4 (D2 on NodeMCU/WeMos D1 Mini) <br>
RESET (RESET_N Pin 11) to GPIO5 (D1 on NodeMCU/WeMos D1 Mini) <br>
GND (Pin 13) to GND <br>
VCC (Pin 12) to 3.3V <br>

  ![image](CCLoader.jpg)
3. Use CCLoader.exe to load the CC2541hm10v540.bin to burn the firmware via the NodeMCU to the HM-10 <br>
4. [Help Video](https://www.youtube.com/watch?v=ez3491-v8Og&lc=z23dzv5wvxrkghouvacdp43beqjns0ivud2tbkcab1xw03c010c.1542030938199060) <br>
5. Upgrade to firmware V609 with the Manufactor upgrade tool [HMSoft-10-2541-V609.zip](/HowTo%20Upgrade%20Firmware%20after%20flash%20(V609)/HMSoft-10-2541-V609.zip).  [More Info](https://forum.arduino.cc/index.php?topic=393655.0)<br>  

Flashing CC2530 and CC2531
==========================
Use the files provided in folder `bin` The Hex files are already converted and ready for flash via CCLoader<br>
More [Zigbee](https://www.zigbee2mqtt.io/information/alternative_flashing_methods.html) flash infos
