# Bus_Terminator_for_Unibus_modern_version_M930GW
This is a double-height Flip Chip board which is a modern version of the DEC M930 bus terminator built using surface mount components. 
<br><p>This board was created for use with the RK05 Emulator and RK05 Tester which performs many of the functions of a drive controller. A terminator is plugged into the second slot of the RK05 Tester. Also, a terminator is plugged into the last emulator or real RK05 in the chain of drives attached to either a tester or actual controller. Since the existence of RK05 Emulators and Testers would create a need for more bus terminators, a modern M930 was developed.
<br><p>The pull-up resistors are 1/4W, which are larger in size and power dissipation capability than the pull-down resistors. In a single 178 ohm + 383 ohm termination, the 178 ohm resistor dissipates 140mW when the signal is low and the 383 ohm resistor dissipates only 30 mW when the signal is high. A de-coupling capacitor is located in the center of each column of resistors so that each termination is in close proximity to a capacitor. Robust planes and power distribution traces are used to keep the source and return current flow paths of bus signals as direct as possible.
<br><p>The component reference designators for this board are idential to those in the DEC M930D schematic.
<br><p>A set of Gerber files, BOM, and pick-and-place files are provided so the board can be manufactured easily at discount PCB and board assembly service providers (such as JLCPCB). Only three component types are JLCPCB "Extended Parts". The rest are all JLCPCB "Basic Parts" to minimize assembly cost. This board can be completly manufactured by JLCPCB at a reasonable cost. No additional assembly steps are required. A completely assembled terminator board built by JLCPCB will cost in the range of a few US$ to about 10 US$ per terminator board depending on the quantity of boards ordered.
<br><p>As of 16-June-2023, the current development status is:
<ul>
<li>Received the first build of 10 boards from JLCPCB. Resistance check is good.</li>
<li>Currently testing the terminator with the RK05 disk emulator.</li>
<li>No testing with actual DEC RK05 disk drives has been performed.</li>
<li>No testing with Unibus devices has been performed.</li>
</ul>
