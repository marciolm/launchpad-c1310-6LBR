6LBR is a 6LoWPAN Border Router based on The Contiki Operating System.


This 6LBR repository is a fork of Contiki with additions:


* The Border Router: in examples/6lbr
* A modified sky-websense: in examples/6lbr-demo
* Modifications in core/net related to 6LBR
* Platform definitions for the Nooliberry in platform/nooliberry

This repository is continuously updated with new commits in Contiki. The master 
branch will never be more than a few commits behind the master Contiki. 
To track changes, see the 6lbr branch of our main Contiki fork on GitHub.
Likewise, useful commits for Contiki are submitted back into the official
Contiki repository through pull requests.

* Home: http://cetic.github.com/6lbr
* Documentation: http://github.com/cetic/6lbr/wiki
* Contiki: http://www.contiki-os.org
* Nooliberry: https://github.com/Noolitic/Nooliberry/wiki
* Contiki fork with a 6lbr branch: http://github.com/cetic/contiki

For the connection with the ENC28j60 with the Launchpad, connect:
* ENC MISO - DIO8
* ENC SCK  - DIO10
* ENC MOSI - DIO9
* ENC CS   - DIO14
* 3.3 V  - 3.3V
* GND - GND


