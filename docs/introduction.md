!!! info
	Please note that this hookup guide is for our latest version of the USB RFID Reader. The overall functionality our new board is the same as its predecessor; however, this latest revision requires a different USB driver and features a new USB-C connector.

	If you have original USB RFID Reader with the USB mini-B connector, please refer to thi [hookup guide](https://learn.sparkfun.com/tutorials/sparkfun-rfid-starter-kit-hookup-guide).


!!! warning
	While most of the [ID-innovations read-only Tiny modules](https://www.id-innovations.com/Modules(non%20write).htm), will have an internal antenna; any of the ID-3XX modules will likely require an external antenna to function. Users should consult with the module's datasheet, when purchasing.



The SparkFun RFID USB-C Reader is a simple to use, USB-to-serial breakout board for the [ID-Innovations Tiny, non-write, RFID modules](https://www.id-innovations.com/Modules(non%20write).htm) *(excluding the Mifare readers, marked with an **MF**)*. This board features a USB-C connector with a CH340C USB-to-serial chip; and comes with an LED and buzzer to indicate card reads, which can be disabled if necessary.

In this guide we'll cover how to utilize the USB-C RFID Reader with a ID-Innovations RFID RFID module. To follow along with this tutorial you'll only need the following items:

- [SparkFun RFID USB-C Reader](https://www.sparkfun.com/sparkfun-rfid-usb-c-reader.html)
- ID-Innovations Tiny, non-write, RFID module
	- [ID-3LA](https://www.sparkfun.com/rfid-reader-id-3la-125-khz.html) *(requires external antenna)*
	- [ID-12LA](https://www.sparkfun.com/rfid-reader-id-12la-125-khz.html)
	- [ID-20LA](https://www.sparkfun.com/rfid-reader-id-20la-125-khz.html)
- Compatible RFID Tag
	- [RFID Tag](https://www.sparkfun.com/rfid-tag-125khz.html)
	- [RFID Button - 16mm](https://www.sparkfun.com/rfid-button-16mm-125khz.html)  
	- [RFID Glass Capsule](https://www.sparkfun.com/rfid-glass-capsule-125khz.html)
- USB cable


## Topics
This document contains two main sections: **Quickstart Guide** and **Hardware** sub-sections.

- The **Quickstart Guide** assumes a working knowledge of development boards and the required software to program them for your project's needs. It covers the basic hardware information and assembly instructions users would need to get started with this product.
- The **Hardware** sections provide:
	- An overview of the USB-C RFID Reader board and its major components. Refer to this page for information on the pin layout and solder jumpers.
	- Assembly instructions to utilize this product with a ID-Innovations Tiny, non-write, RFID module *(excluding the Mifare readers, marked with an **MF**)*.


## Resources and Support
You'll find the board design files (KiCad files & schematic), relevant documentation (datasheets, white papers, etc.) and other helpful links on the [Resources page](./resources.md). Lastly, the **Support** section includes a [Troubleshooting page](./troubleshooting_tips.md) that includes any helpful tips specific to this board as well as information on how to receive technical support from SparkFun.
