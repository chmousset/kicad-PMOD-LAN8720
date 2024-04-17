# PMOD-LAN8720
![3D render](doc/3D%20render.png "3D rendering")
This is a single-width PMOD module with the RMII 10/100BASE-T PHY LAN8720. Contrary to most similar Ethernet PHY extensions, this one requires the refclk signal has to be provided from the host. It can be useful when multiple PHY have to be connected as it can reduce usage of clock-domain crossing.

## Configuration
The configuration straps are set for RMII slave operation, and link autonegociation. The MDIO is broken down on an extra connector for diagnostic or testing purposes. PHY ID 0 is used.
