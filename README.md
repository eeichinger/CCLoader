CCLoader
========

Burn CC254x firmware using an NodeMCU board.

1. Load the CCLoader Arduino sketch to the MCU board.
2. Wire the pins:

DD to GPIO14 (D5 on NodeMCU/WeMos D1 Mini) <br>
DC to GPIO4 (D2 on NodeMCU/WeMos D1 Mini) <br>
RESET to GPIO5 (D1 on NodeMCU/WeMos D1 Mini) <br>
LED to GPIO2 (D4 Blue LED on the WeMos D1 Mini and the ESP-12E module on the NodeMCU) <br>

  ![image](CCLoader.jpg)
3. Use CCLoader.exe to load the CC2541hm10v540.bin to the MCU board and the board will burn the firmware to the HM-10 <br>
4. [Help Video](https://www.youtube.com/watch?v=ez3491-v8Og&lc=z23dzv5wvxrkghouvacdp43beqjns0ivud2tbkcab1xw03c010c.1542030938199060) <br>
5. Upgrade to firmware V609 with the Manufactor upgrade tool [HMSoft-10-2541-V609.zip](/Bin/HMSoft-10-2541-V609.zip).  [More Info](https://forum.arduino.cc/index.php?topic=393655.0)<br>  
