# Project-Flight_DFM
Manufacturing information for the Flight system 

#### [Flight_Assembly_BoM](Flight_Assembly_BoM.csv)
Bill of Materials for full system assembly 

#### Custom Parts Required:
- [Logger Box](./Box)
- [Mounting Plate](./Box)

#### Sub Assemblies Required:
- [Kestrel Board, v1.7](https://github.com/gemsiot/DFM_-_Kestrel)
- [Gonk Board, v1.2](https://github.com/gemsiot/DFM_-_Gonk-18650-1S3P)
- [SDI-12 Talon, v1.4](https://github.com/gemsiot/DFM_-_Talon-SDI12)
- [I2C Talon, v2.1](https://github.com/gemsiot/DFM_-_Talon-I2C)
- [Aux Talon, v1.4](https://github.com/gemsiot/DFM_-_Talon-Aux)

## System Assembly

- All parts required for system assembly are detailed in [Flight_Assembly_BoM](Flight_Assembly_BoM.csv)
- After all sub assemblies are finished, complete the following steps 
1. Prepare main data logger board using assembly instructions detailed in [Kestrel Assembly Video](https://drive.google.com/open?id=1bD3Pa5R_5ufvpw4cUTz-tKCreJj2a7cN&authuser=schu3119%40umn.edu&usp=drive_fs)
2. Prepare mounting plate (if necessary) using instructions detailed in [Mounting Plate Prep Video](https://drive.google.com/open?id=1bFxcQoePnDuSZhUtLkiAZ8WnBKMtT0PU&authuser=schu3119%40umn.edu&usp=drive_fs)
3. Place antennas onto the mounting plate as detailed in [Antenna Placement Video](https://drive.google.com/open?id=1bRhHP4KZSppHAmR2KgFZIg572g8hdObi&authuser=schu3119%40umn.edu&usp=drive_fs)
4. Attach first layer of components to mounting plate as detailed in [Mounting Plate Assembly](https://drive.google.com/open?id=1bT006Io6QUtz_VcvTtEhTx-1zirhanhX&authuser=schu3119%40umn.edu&usp=drive_fs)
5. Install Talon boards into logger box as detailed in [Talon Install](https://drive.google.com/open?id=1bXs4N-supN-SKw3k3KqC6i_FpCVYv-39&authuser=schu3119%40umn.edu&usp=drive_fs)
	- __All Talon nuts should be torqued to 1.0Nm__
6. Install cable gland in logger box as detailed in [Cable Gland Install](https://drive.google.com/open?id=1baKlFoLFSimpsM3mUY0MrUyb_E4Ifo47&authuser=schu3119%40umn.edu&usp=drive_fs)
	- __Cable gland should be tightened to logger box with torque of 1.6Nm__
7. Install prepared mounting plate into logger box as detailed in [Mounting Plate Install](https://drive.google.com/open?id=1aQjAO0VGxeccukH69H0SHO_HMsZDXyN0&authuser=schu3119%40umn.edu&usp=drive_fs)
8. Install prepared main data logger as detailed in [Kestrel Install](https://drive.google.com/open?id=1aqM2ey-8seV0-pxXx1Z-ZSsXYQLJVgyQ&authuser=schu3119%40umn.edu&usp=drive_fs)
	- __Switch nut should be tightened with a torque of 0.7Nm__
	- __USB screws should be tightened with a torque of 0.3Nm__
9. Make connections between main data logger and Talons using cable assemblies as described in [Talon Cable Connection](https://drive.google.com/open?id=1b7LckyKWHlNqdWrOU5_O6cfOPqYJ8c6I&authuser=schu3119%40umn.edu&usp=drive_fs)
10. Perform final assembly steps given detailed description in [Final Assembly](https://drive.google.com/open?id=1bCYssfYtOqvqFnKVWkBEIiFjV94_6-FX&authuser=schu3119%40umn.edu&usp=drive_fs)
	- __Cable gland cap should be tightened with a torque of 1.0Nm__
	- __Lid screws should be tightened with a torque of 0.9Nm__

