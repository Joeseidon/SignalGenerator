# ThreePhase Signal Generator - Phase Control Updates:
====================================================
#To Upload GUI to Raspberry Pi:
	-> Locate the ThreePhase.py and ThreePhase.ui files in this dir.
	-> Place both files on a flash drive.
	-> Plug the flash drive into the Raspberry Pi
	-> Create a new folder on the Raspberry Pi and copy both files into it.
		->Note: For the GUI to function properly these files must be together.
		
#To Load the CCS Project onto the Launchpad:
	-> Locate the SignalAnalysisStation_ThreePhaseGen folder in this dir
	-> Upload this CCS project to the CCS IDE or the CCS Cloud IDE if you do not have CCS installed.
	-> Before uploading this program, make sure you have 2837xS_Generic_FLASH_lnk enabled and 2837xS_Generic_RAM_lnk disabled. 
		->If you wish to load to RAM instead you must open the device.h file in the device folder and comment out #define _FLASH 1 and flip the disabled files above.
	-> Once the program has been successfully loaded the system should perform as before. There are no external connection changes
