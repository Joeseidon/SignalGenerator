# ThreePhase Signal Generator - Phase Control Updates:
====================================================
# To Upload GUI to Raspberry Pi:
	-> Perform a git clone for this repository on the Raspi or copy the ThreePhase.py and .ui files to the Raspi. 
	As long as the .py and .ui files are in the same dir the GUI can
	be run using a terminal call: sudo python3 ThreePhase.py
# To Load the CCS Project onto the Launchpad:
	-> Locate the SignalAnalysisStation_ThreePhaseGen zip foler in this repo.
	-> Unzip this file.
	-> Upload this CCS project to the CCS IDE or the CCS Cloud IDE if you do not have CCS installed.
	-> Before uploading this program, make sure you have 2837xS_Generic_FLASH_lnk enabled and 2837xS_Generic_RAM_lnk disabled. 
		->If you wish to load to RAM instead you must open the device.h file in the device folder and comment out #define _FLASH 1 and flip the disabled files above.
	-> Once the program has been successfully loaded the system should perform as before. There are no external connection changes
