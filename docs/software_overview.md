## USB Driver
Users will need to install a USB driver for the CH340C serial-to-USB chip, in order to communicate with the RFID module. The latest USB drivers for the CH340C are available from the manufacturer, on the [WCH website](https://www.wch-ic.com/products/CH340.html?):


<div class="grid cards" align="center" markdown>

-   :material-microsoft-windows: **Windows**

	---

	[:octicons-download-16:{ .heart } Download `CH341SER.EXE`](https://www.wch-ic.com/downloads/CH341SER_EXE.html){ .md-button .md-button--primary target="blank" }


-   :material-apple: **MacOS**

	---

	[:octicons-download-16:{ .heart } Download `CH341SER_MAC.ZIP`](https://www.wch-ic.com/downloads/CH34XSER_MAC_ZIP.html){ .md-button .md-button--primary target="blank" }


-   :material-linux: **Linux**

	---

	[:octicons-download-16:{ .heart } Download `CH341SER_LINUX.ZIP`](https://www.wch-ic.com/downloads/CH341SER_LINUX_ZIP.html){ .md-button .md-button--primary target="blank" }

</div>


???+ abstract "Need Directions?"
	For users having trouble installing the CH340 USB driver, check out our video and hookup guide:

	<div class="grid" markdown align="center">

	<div markdown>

	<div class="video-500px">
	<iframe src="https://www.youtube.com/embed/MM9Fj6bwHLk" title="Tutorial: Installing CH340 Drivers" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	</div>

	</div>

	<div class="grid cards" markdown>

	-   <a href="https://learn.sparkfun.com/tutorials/908">
		<figure markdown>
		![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/9/0/8/USB-to-serial_converter_CH340-closeup.jpg)
		</figure>

		---

		**How to Install CH340 Drivers**</a>

	</div>

	</div>



## Terminal Emulator
In order to read the `ASCII` data output from an RFID module, for when a RFID tag is read, users will need to install a [serial terminal emulator](https://learn.sparkfun.com/tutorials/terminal-basics) on their computer.

<div class="grid cards" markdown>

-   <center>:material-microsoft-windows: **Windows**</center>

	---

	For Windows computers, we highly recommend [TeraTerm](https://teratermproject.github.io/index-en.html).


-   <center>:material-linux: **Linux**</center>

	---

	Some Linux operating systems may already have the `screen` terminal emulator preinstalled.

</div>


!!! abstract "Need Directions?"
	Check out our hookup guide to install your favorite terminal emulator:

	<div class="grid cards" markdown align="center">

	-   <a href="https://learn.sparkfun.com/tutorials/112">
		<figure markdown>
		![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/1/2/thumb.jpg)
		</figure>

		---

		**Serial Terminal Basics**</a>

	</div>


### Read an RFID Tag
To display the ASCII data output properly, users will need to connect to the `COM` port of the USB-C RFID Reader and configure the port settings to **9600bps** `8`-`N`-`1`. Once configured properly, users can scan compatible RFID tags and their unique ID will be displayed in the terminal emulator.

<div class="grid" markdown>

<div markdown>

<figure markdown>
[![Reading an RFID tag](./assets/img/hookup_guide/assembly-scan.jpg){ width="500" }](./assets/img/hookup_guide/assembly-scan.jpg "Click to enlarge")
<figcaption markdown>Scan an RFID tag with the USB-C RFID Reader.</figcaption>
</figure>

</div>


<div markdown>

<figure markdown>
[![Tag ID displayed in terminal](./assets/img/hookup_guide/demo-read_tags.gif){ width="700" }](./assets/img/hookup_guide/demo-read_tags.gif "Click to enlarge")
<figcaption markdown>The unique ID of RFID tags being displayed in the terminal emulator.</figcaption>
</figure>

</div>

</div>
