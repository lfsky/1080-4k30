	4k30


A modified version of chimera which restores a few features how they were intended to get seen.

	• Reverted interpolation
	• Reverted camera fixes
	• Reverted contrail fixes
	• Reverted Gamma lock
	• Restored 1103 waves
	
A more appropriate way to do this would utilize chimera_tps (ticks per second) of HALO then 
slow everything down 1/2 for 60hz or 1/4 for 120 hz to remain consistent with rendering. However,
this is beyond the scope of current programming knowledge and also would require a top of
the line system to consistently achieve this playable framerate in the most ideal circumstances.

This project will evolve over time to as chimera does and will eventually lock the framerate to 
avoid confusion altogether as a seperate unique version for an intended purpose exclusively.

NOTE GAMMA LOCK AFFECTS THE OS AND REQUIRES RESTART TO RESET VALUES TO DEFAULT
 
What it does over the regular chimera version to maintain consistency with the 2003 version.
 
	1102 mipmap ripples intensity at high resolution on the horizon waves while scoping.
	Forces interpolation off intended for stronger framebuffer effects locked 30 framerate.
	Reverts any enhancers associated with those unused, restoring regular PC functionality.


Install placing everything inside the selection folder into


	CE\


Overwrite all files, keep a copy of your strings.dll just in case needing to revert or pick and choose.


Developed Exclusively for HALO NV2A

v. 1080

lfsky
