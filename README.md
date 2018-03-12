#  Internet of Things Smart City Mesh Root Firmware Core

This IoT Firmware Core enables mesh root functionality on your TI CC13xx MCU based product using the Sub-GHz ISM radio band.  Mesh root functionality allows you to connect your Mesh Node devices to the Internet.  Use at least one Mesh Root within range of at least one Mesh Node to complete your Smart City Mesh Network rollout.

See also the Mesh Node [companion repository](https://github.com/firmwaremodules/iot-mesh-node).

## Evaluation Firmware

The evaluation firmware available in this repository is free to use on the specified evaluation platform.  Without an authorization key, the firmware will run for 30 minutes before the radio shuts off.  Simply contact us to receive a free authorization key to enable unlimited evaluation or educational use. Send your device's EUI/UID as reported in the console and we will promptly generate the authorization key specific to your device.

Note that evaluation firmware provided in this repository uses a fixed and public MAC-layer AES-128 security key as specified below. [TBD]


## How Does The Mesh Root Work?

The Smart City Mesh Root Firmware Core communicates to other Mesh Nodes within range of its Sub-GHz radio using an advanced IoT mesh network system called 6LoWPAN.  The Mesh Root also connects to the regular internet using a traditional Ethernet "backhaul" communication link.  Packets are transparently forwarded between the two interfaces.  A Mesh Root need only be within range of one Mesh Node.  The Mesh Root will formward packets to one or more Mesh Nodes.  The Mesh Nodes will continue to propagate the packet until the destination is found. 

## Why Use Devices With Mesh Root Firmware Cores?

You can build your network out quickly with the long range Sub-GHz radio technology, and each device is easily accessed using standard internet protocols. Compared to competing mesh network technologies, the Smart City Mesh Root Firmware Core offers best-in-class power consumption, security and range.  With this system you can eliminate the use of cellular communication technology's cost, complexity and high power consumption.

