# Misc-Percussion
This is the Robot Orchestra repo for files relating to the percussion suite robot(s). Currently the percussion suite comprises the following units:
- Tambourine
- Woodblock
- Triangle
- Cowbell
- 3 sections of Xylophone

These instruments are being grouped together due to their similar interfaces and needs. 
The goal is to have a single controller, attached to a single PCB, which controls all of the above elements using a common software interface. 
The hardware and software are designed to be modular and expandable, so that the instruments not being used for a given peice can be removed and reshuffled easily. 
All instruments have a common need for a motor that hits, following a simple control mechanism. Triangle and tambourine will also need motors to dampen them, and the tiny cowbell may need to be shaken.

**To Do**
- Design PCB for hardware controller
- Finalise hardware arrangements for basic hitting of triangle, xylophone
- Create software interface for basic hitting
- Rework tambourine and woodblock hardware to be less janky
- Expand software to allow for a range of dynamics
- Expand robot hardware to allow for dampening
