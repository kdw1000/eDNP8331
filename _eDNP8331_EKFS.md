# eDNP/8331: First Steps with the eDNP/8331-EK 

...

![Overview](https://ssv-comm.de/forum/bilder/8331EK-connect.png)

## Serial Console Session

Use of the serial console requires an RS232 interface connection between the eDNP/8331-EK board and the user's PC. The setup parameters **115,200 bps, 8N1** apply to this connection. Furthermore, terminal emulator software such as Tera Term or PuTTY is required on the PC (see also https://en.wikipedia.org/wiki/Tera_Term).

![Overview](https://ssv-comm.de/forum/bilder/8331EK-Serial.png)

To request the eDNP/8331 Linux operating system to issue a login prompt in the terminal emulator window, the PC's Enter key must first pressed one time. Then you can log in with user name and password. The two entries required for this login can be found on a label sticker on the back of the eDNP/8331-EK board.

After a successful login with username and password, any eDNP/8331 Debian Linux commands can be executed via command line within the serial console session.

## SSH Client Session

Analogous to the serial console session, an SSH client session via Ethernet LAN is also possible using the factory default IP address **192.168.0.126** of the eDNP/8331-EK board. The integrated SSH client from Tera Term can be used for this purpose, for example.

An SSH client session also requires a login first. The two entries required for this can also be found on a label sticker on the back of the eDNP/8331-EK board.

![Overview](https://ssv-comm.de/forum/bilder/8331EK-SSH.png)

After a successful login with username and password, any eDNP/8331 Debian Linux commands can be executed via command line within the SSH client session.

## SFTP Client Session

...

![Overview](https://ssv-comm.de/forum/bilder/8331EK-SFTP.png)

## Connectors, Slots and Wireless Modem

...

![Overview](https://ssv-comm.de/forum/bilder/8331EK-explore.jpg)

**(1)** SIM card slot for the miniPCIe slot **(6)**.

**(2)** System IO: 1x I2C, 1x UART (TTL interface with RXD, TXD).

**(3)** DNP/8331 with A/B boot loader, Debian operating system, SSV/WebUI, Python runtime environment (DNP/8331-EVA firmware).

**(4)** 1x 10/100 Mbps Ethernet LAN with 1x status LED (Link, Activity).

**(5)** 1x UART (RS232 interface with TXD, RXD, RTS, CTS).

**(6)** 1x miniPCIe slot for wireless modem modules (e.g. 4G, LTE Cat M1 or NB-IoT modem).

**(7)** 2x LED, one of them controllable by software, the other LED indicates the power-on state.

**(8)** 24 VDC power supply, 1x UART (RS485 interface).

**(9)** Option: Wireless modem module for miniPCIe slot **(6)**. 

**(e)DNP/8331 Hardware Reference:** https://www.ssv-embedded.de/doks/manuals/hr_dnp8331_en.pdf

**MB/941 Hardware Reference:** https://www.ssv-embedded.de/doks/manuals/hr_mb941_en.pdf