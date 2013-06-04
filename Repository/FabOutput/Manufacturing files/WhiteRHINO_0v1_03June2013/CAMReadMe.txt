!!! BEFORE STARTING, READ THIS FILE COMPLETELY !!!

ReadMe File

Customer:       University of Capetown
Date:		14/05/13
Project Name:   WhiteRHINO_0v1
Release:        A (document)


PCB Layout:		Altium V13
CAM System:		CAMtastic
------------------------------------------------------------------------

==============================================================================

 ____________________________________________________________________
|                             DATA FORMAT                            |
|--------------------------------------------------------------------|
|                              | GERBER DATA      | DRILL DATA       |
|==============================|==================|==================|
| format                       | RS-274-X         | N/A              |
| Coordinate Type              | RELATIVE         | RELATIVE         |
| Dimensions                   | METRIC           | METRIC           |
| Zero Suppression             | LEADING          | LEADING          |
| Format Digits	               | 2(int), 5(fract) | 2(int), 5(fract) |
| PLOTTER TYPE                 | UNSORTED(RASTER) | N/A              |
|____________________________________________________________________|



Quantity
--------

1 board.

------------------------------------------------------------------------------------------
   FILE	(.layer extension)      DESCRIPTION                
------------------------------------------------------------------------------------------
Gerber Files (note board outline is included in all layers)
------------

\Gerber Files\                  Directory
  WhiteRHINO_0v1.apr            Aperture Data
  WhiteRHINO_0v1.GTL            Top Layer                               
  WhiteRHINO_0v1.G1             Mid Layer 1                                
  WhiteRHINO_0v1.G2             Mid Layer 2   
  WhiteRHINO_0v1.G3             Mid Layer 3 
  WhiteRHINO_0v1.G4             Mid Layer 4
  WhiteRHINO_0v1.G5             Mid Layer 5                                                          
  WhiteRHINO_0v1.GBL            Bottom Layer                            
  WhiteRHINO_0v1.GTO            Top Overlay                             
  WhiteRHINO_0v1.GTP            Top Paste                               
  WhiteRHINO_0v1.GTS            Top Solder                              
  WhiteRHINO_0v1.GBS            Bottom Solder                           
  WhiteRHINO_0v1.GBP            Bottom Paste                            
  WhiteRHINO_0v1.GBO            Bottom Overlay
  WhiteRHINO_0v1.GM1            Mechanical Layer 1
  WhiteRHINO_0v1.GM13           Mechanical Layer 13
  WhiteRHINO_0v1.GM15           Mechanical Layer 15
  WhiteRHINO_0v1.GM16           Mechanical Layer 16
  WhiteRHINO_0v1.GP1            Plane Layer 1
  WhiteRHINO_0v1.Gp2            Plane Layer 2
  WhiteRHINO_0v1.Gp3            Plane Layer 3
  WhiteRHINO_0v1.Gp4            Plane Layer 4
  WhiteRHINO_0v1.Gp5            Plane Layer 5                            
          
                                       
Drill files: 
------------

\NC Drill Files  - directory
  WhiteRHINO_0v1.TXT    - Top Layer to Bottom Layer (txt)
  WhiteRHINO_0v1.DRR    - Drill report
  WhiteRHINO_0v1.LDP    - LDP File

ODB ++ Files
------------
(as an alternative to using the Gerber + NC Drill files)

\OSB++ Files  - directory
  \odb        - directory including the full ODB++ database for the board
  WhiteRHINO_0v1.zip - zip file of the odb directory.
  
									   
Other files included:
---------------------
\Drill Drawing                 - Directory
 WhiteRHINO_0v1_FabDwg.PDF     - PDF of Fab drawing
\Test Point Report             -Directory
 Fabrication Testpoint Report for WhiteRHINO_0v1.ipc        - IPC-D-356 Test Point netlist file Netlist file
\                              -Directory

Board Stackup
--------------
Board is a 12 layer board with total thickness of 1.434 MM.
Please see WhiteRHINO_0v1_FabDwg.PDF (PDF of Fab drawing) for stackup details and manufacturing notes.

  
OTHER NOTES:
-README files may contain instructions which are rejection criteria if ignored
-Manufacturer's responsibility to read and transfer information in these files to all those with a need to know
-All data questions (Pre-Cam Review, EQ) will be sent to all of the below contacts for approval prior to starting board fabrication
-Supplier to confirm all verbal decisions with reply email

Primary CONTACTS:
Dr. Alan Langman   (Principal)  University of Capetown   alan.langman@gmail.com
Ojonav Hazarika			University of Capetown	 hazarika.ojonav@gmail.com

