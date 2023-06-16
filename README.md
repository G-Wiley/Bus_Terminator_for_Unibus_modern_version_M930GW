# Bus_Terminator_for_Unibus_modern_version_M930GW
This is a double-height Flip Chip board which is a modern version of the DEC M930 bus terminator built using surface mount components. 
<br><p>The pull-up resistors are 1/4W, which are larger in size and power dissipation capability than the pull-down resistors. A de-coupling capacitor is located in the center of each column of resistors so that each termination is in close proximity to a capacitor. Robust planes and power distribution traces are used to keep the source and return current flow paths of bus signals as direct as possible.
<br><p>The component reference designators for this board are idential to those in the DEC M930D schematic.
<br><p>A set of Gerber files, BOM, and pick-and-place files are provided so the board can be manufactured easily at discount PCB and board assembly service providers (such as JLCPCB). Only three component types are JLCPCB "Extended Parts". The rest are all JLCPCB "Basic Parts" to minimize assembly cost. This board can be completly manufactured by JLCPCB at a reasonable cost. No additional assembly steps are required.
<br><p>As of 16-June-2023, the current development status is:
<ul>
<li>Received the first build of 10 boards from JLCPCB. Resistance check is good.</li>
<li>Currently testing the terminator with the RK05 disk emulator.</li>
<liNo testing with actual DEC RK05 disk drives has been performed.</li>
<li>No testing with Unibus has been performed.</li>
</ul>
