# This repo is obsolete, 
# please use https://github.com/Nuvoton-Israel/bootblock instead.



-----------------------------------------------------------------------------
Nuvoton Technology Corporation - Confidential
NPCM7XX (Poleg) BootBlock Release Letter
Copyright (c) 2013-2018 Nuvoton Technology Corporation. All Rights Reserved.
-----------------------------------------------------------------------------

NPCM7XX bootBlock Package
Release Letter
Version: 10.08.07
Date:    May 2018

This package is released under the terms of the Source Code License Agreement,
signed between Nuvoton and your company.


PACKAGE CONTENTS
----------------
This package contains the following files/folders:
- BootBlock_Sources_RelLetter.txt                     - This release letter
- Images\Poleg_bootblock.bin                          - Output image bin


DESCRIPTION
-----------
This package contains the Nuvoton Poleg bootBlock for the NPCM7XX.
This package is released in beta quality.
The BootBlock meets the security requirements as specified in SecureBootNuvoton_201401216.docx

Inside the binary there is a change log at offset 0x40 of Poleg_bootblock.bin in text format (in addition to the version at offset 0xF4).
If the BootBlock is loaded to chip you can view it via u-boot or JTAG at address 0x80000240.


REQUIREMENTS
------------
Hardware: One of the following chips:
- A Nuvoton NPCM750 A1 Silicon version BMC device. 
- A Nuvoton NPCM730 A1 Silicon version BMC device. 


INSTALLATION PROCEDURE
----------------------
After compilation (see HowToBuild.txt) program   deliverables\bootblock\Images\Poleg_bootblock.bin
to flash via the programming scripts or other means.


-----------------------------------------------------------
For contact information see "Contact Us" at www.nuvoton.com
-----------------------------------------------------------
