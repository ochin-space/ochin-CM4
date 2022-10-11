![Alt text](images/logo.png?raw=true&=200x "ochin_CM4")
# ochin_CM4
The öchìn CM4 it’s a tiny carrier board for the Raspberry Pi Compute Module  It is designed for applications where a powerful machine with low consumption and small dimensions is required. The small form factor makes it interesting for all those applications where the space available is not much and containing the weight is important, such as in robotics, home automation and IOT.
![Alt text](images/ochin_CM4_topDoc.png?raw=true "ochin_CM4")
The board is compatible with all Raspberry Pi CM4 modules equipped with eMMC. Depending on your needs, you can select a CM4 module with an SDRAM starting from 1GB up to 8GB and the eMMC from 8GB up to 32GB, with or without the Wi-Fi / BT4 connection.

Key features of the Raspberry Pi CM4 available on öchìn are as follows:
* Broadcom BCM2711, Quad core Cortex-A72 (ARM v8) 64-bit SoC @ 1.5GHz
* Small Footprint 55mm × 40mm × 4.7mm module
* H.265 (HEVC) (up to 4Kp60 decode), H.264 (up to 1080p60 decode, 1080p30 encode)
* OpenGL ES 3.0 graphics
* Options for 1GB, 2GB, 4GB or 8GB LPDDR4-3200 SDRAM with ECC
* Options for 8GB, 16GB, or 32GB eMMC Flash
o Peak eMMC bandwidth 100MBytes/s
o 2.4 GHz, 5.0 GHz IEEE 802.11 b/g/n/ac wireless
o Bluetooth 5.0, BLE
o On board electronic switch to select between PCB trace or external antenna
* 1×USB 2.0 port (highspeed)
* MIPI CSI-2:
o 1×2-lane MIPI CSI camera port, 1×4-lane MIPI CSI camera port
* 1×USART, 3×UART, 1×I2C port, 1×SPI port, Analog Video Output

In this repository you can find the manual of the board, a quick start guide for flashing the CM4 module and a guide with some tips on how to make the connections to the ochin board. 

It is important to read them both before turning on the ochin_CM4 board, to know its characteristics and above all the sequence in which the signals are present on the connectors.

# Community

Feel free to join the öchìn CM4 [Discord](https://discord.gg/Uj9XfSwn) group with members helping each other.



# Important!!!

The ochin_CM4 board must be used with a Raspberry Pi CM4 module with eMMC (the lite version is not good), there is no slot for the microsd card onboard. The reasons for this choice are explained in the manual and concern the optimization of spaces and the efficiency of the internal flash.

Print and use the extractor for the CM4 module if you don't want to break the mezzanines, you can find the .stl in the "3d/Covers turrets and extractors" section of this repository.

Take a look at the "öchìn CM4 - Wiring and Suggestions.pdf" before power the board on, it may save your time and your devices.

Never trust the color code of the GHS cables, the sequence in which commercial GHS cables are assembled is often random and does not reflect the sequence of the signals present in the connectors of the ochin_CM4 board.
