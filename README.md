# Bus_Terminator_for_Unibus_modern_version_M930GW
This is a modern version of the DEC M930 bus terminator. It's a double-height Flip Chip board built using surface mount components.
![image](https://github.com/G-Wiley/Bus_Terminator_for_Unibus_modern_version_M930GW/assets/99116236/9c54bdee-ea85-4d74-81f5-cb38064fd00f)

<br><p>This board was created for use with the RK05 Emulator and RK05 Tester which performs many of the functions of a drive controller. Since it is electrically identical to the original M930 it could, in theory, also be used as a Unibus terminator but has not been tested in a Unibus application. 
<br><p>In systems using the RK05 Emulator and Tester, a terminator is plugged into the second slot of the RK05 Tester. Also, a terminator is plugged into the last emulator or real RK05 in the chain of drives attached to either a tester or actual drive controller (such as an RK8-E or RK11-D). Since the existence of RK05 Emulators and Testers would create a need for more bus terminators, a modern version of the M930 was developed.
<br><p>The pull-up resistors are 1/4W, which are larger in size and power dissipation capability than the pull-down resistors. In a single 178 ohm + 383 ohm termination, the 178 ohm resistor dissipates 140mW when the signal is low and the 383 ohm resistor dissipates only 30 mW when the signal is high. A de-coupling capacitor is located in the center of each column of resistors so that each termination is in close proximity to a capacitor. Robust planes and power distribution traces are used to keep the source and return current flow paths of bus signals as direct as possible.
<br><p>The component reference designators for this board are identical to those in the DEC M930D schematic.
<br><p>A set of Gerber files, BOM, and pick-and-place files are provided so the board can be manufactured easily at discount PCB and board assembly service providers (such as JLCPCB). Only three component types are JLCPCB "Extended Parts". The rest are all JLCPCB "Basic Parts" to minimize assembly cost. This board can be completly manufactured by JLCPCB at a reasonable cost. No additional assembly steps are required. A completely assembled terminator board built by JLCPCB will cost in the range of a few US$ to about 10 US$ per terminator board depending on the quantity of boards ordered.
<br><p>As of 29-October-2023, the current development status is:
<ul>
<li>Received the first build of 10 boards from JLCPCB. Resistance check is good.</li>
<li>The terminator has been tested extensively with the RK05 disk emulator and RK05 tester and functions perfectly.</li>
<li>No testing with actual DEC RK05 disk drives has been performed.</li>
<li>No testing with Unibus devices has been performed.</li>
</ul>
