
# Notes

## Power System

Battery
Most 5” drones are powered off of 4s or 6s Lipo Batteries
Balance charger required to charge batteries
Each cell must be charged equally
Voltage range per cell usually between 3.5v to 4v 
Storage voltage is roughly 3.8v per cell

Power Distribution Board (PDB)
Most common connection to battery is XT-60
Distributes regulated power
Usually paired with a 4 in 1 ESC

Electronic Speed Controller (ESC)
Takes in power from PDB
ESC controls and distributes power to a motor

Motors
1700KV to 1900KV motors are best for 6s builds
Higher KV motors for lower cell batteries 
Higher KV = higher RPM @ lower torque
Long range = lower KV motors + large props and battery

Props
5 inch build, 5 inch props
5 inch refers to diameter
2 Clockwise (CW) props and 2 Counter Clockwise (CCW) props needed 


## Video System

Analog Systems (analogue signals)
Lower latency
More widely available from a variety of dealers
Cheaper

Digital Systems (digital signals)
Higher picture quality and less interference
Walksnail, DJI, HDZero
Expensive 

Camera 
Just get a popular one
Common video ratios are 4:3 or 16:9
Check native field of view ratio (FOV)

Video Transmitter (VTX)
mW of power determine range and power
500 mW is good enough
5.8 GHz band 
Check the operational voltage range

Antenna (TX)
Different polarisation
linearly polarised antennas (LP), or omni-directional antenna
circularly polarised antennas (CP)
left hand circular polarised antennas (LHCP)
right hand circular polarised antennas (RHCP)
Polarisation helps to reduce interference by targeting a specific output direction
Different types of connection
MMCX, snap on and pretty solid
SMA, screw on and very study
UFL, lightweight and prolly gonna break


## Flight Controller

Flight Controller (FC)
Connects direction to the power distribution board
Provides and receives inputs from all components
The brain
Check the operational voltage range


## Receiver system

Frame
Different sized frames

Receiver (RX)
Different types of radio control protocols
TBS CrossFire
TBS Tracer
FrSky ACCST
Most common protocol is ELRS (ExpressLRS)
Standard transmission bands are 915 MHz or 2.4GHz
915 MHz for long range
Lower frequency increases range
Greater risk of interference when flying in groups
2.4 GHz for less latency
Greater bandwidth
Can be interfered by wifi signals


## User

Controller
- Requires the same receiver protocol as the receiver (RX)

FPV Goggles
- box goggles
- Low profile goggles

Video Receiver

Antenas



xt60 connector for power
6 to 4 cell battery
1800 kv motor for 6s battery

- Capacitor for voltage spikes and video noise


Flight controller has everything


Motor <- Speed Controller (ESC) <- Power Dist. Board <- xt60 connector <- Battery

-----
Frame














