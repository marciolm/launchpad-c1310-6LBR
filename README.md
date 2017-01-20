6LBR is a 6LoWPAN Border Router based on The Contiki Operating System.

This repository is intended only to document the modifications I made in original CETIC´s 6LBR code to build a standalone 6LBR without a host (like Raspberry Pi or BBB), just jumping a cheap ENC28j60 module to a Launchpad cc1310 board.

I also changed the default frequency and channel to my country in dot-15-4g.h files, but it´s optional. 

To connect the ENC28j60 with the Launchpad, use dupont cables (female-female) between these pins:
* ENC MISO --> DIO8
* ENC SCK  --> DIO10
* ENC MOSI --> DIO9
* ENC CS   --> DIO14
* 3.3 V  - 3.3V
* GND - GND


CETIC 6LBR links:

* Home: http://cetic.github.com/6lbr
* Documentation: http://github.com/cetic/6lbr/wiki
* Contiki: http://www.contiki-os.org
* Nooliberry: https://github.com/Noolitic/Nooliberry/wiki
* Contiki fork with a 6lbr branch: http://github.com/cetic/contiki



