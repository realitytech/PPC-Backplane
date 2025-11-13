# PPC-Backplane
Amstrad PPC640 and PPC512 Internal PC104 Backplane

<img width="3642" height="1949" alt="M1510251 - PPC Conn" src="https://github.com/user-attachments/assets/a867e1c3-8ac7-4f86-89ae-155b51ce8d28" />


This adds an internal PC104 compatible slot to the PPC640 and PPC512 in the modem bay.
The board is designed to fit inside the machine soldering on the underside of the main board but can be fitted with through hole sockets and used externally too for testing and development.

This is the inital release version and corrects a few issues with the very first issue. The schematic and PCB need tidying.

NOTE: This version is UNTESTED and has not been built yet. It *should* work as it's an evolution of a design that DOES work. However it's missing changes that the test board has, notably.
Pullups on A8-A16, these seem to be not needed on all units.
Pullups on D0-D7 are optional, both units I have here already have these on the board.

The plan is to move to 74xxx16245 chips to keep to two chips but buffer ALL lines.

Licence/Useage:
Please credit the source. This is a non-commercial project and you may do with it as you wish for PERSONAL USE ONLY
Commercial use is strictly forbidden.
