# NEUROSTAT/3D-SSP
Neuroimaging and Biotechnology Laboratory (NIBTL)  
Department of Radiology and Imaging Sciences, University of Utah, Salt Lake City, UT, U.S.A.

# About NEUROSTAT

 

         NEUROSTAT is a software library for neurological and biomedical image analysis that has been developed over the past 2 decades.  The software has been used extensively by clinicians and investigators worldwide (40 countries as of 2015), and their results are published elsewhere.  NEUROSTAT includes programs for both basic research applications (e.g., brain mapping studies, group comparison) and clinical research applications (e.g., three-dimensional stereotactic surface projections, 3D-SSP, for image interpretation, coregistration for ictal-interictal SPECT and MRI-PET/SPECT).  Components of NEUROSTAT can be used for other types of biomedical imaging analyses (e.g., oncology imaging, autoradiographic image analysis).   Custom software using NEUROSTAT library has been created by various investigators, and some of them are available in the public domain.

 

         NEUROSTAT programs are provided free of charge to facilitate scientific applications and collaborations among investigators.  However, please note that all programs are protected strictly by copyrights.  No part of NEUROSTAT programs may be used, transferred, disassembled, or modified in any way without prior written permission.  Although NEUROSTAT programs are provided free, investigations and publications concerning the programs themselves, i.e., program algorithms, programming styles, program coding, and program performance, are not permitted without prior written agreement.

 

         Downloadable software in this page is a subset of the larger software library.  If you have a specific request for certain types of programs or analyses, please contact us by e-mail regarding availability.

 

         NEUROSTAT should not be relied upon to solve problems when an incorrect solution could result in injury to a person.  The user assumes all risk and liability associated with the use of NEUROSTAT.  The author of NEUROSTAT disclaims all liability for direct or consequential damages resulting from its use and makes no claims as to the reliability or fitness of NEUROSTAT for any particular use.

 

         To run NEUROSTAT/3D-SSP, you are required to install a valid KEYCODE into the program folder.  KEYCODE is provided free of charge and allows us to keep track of current users.  You may copy KEYCODE for multiple copies of NEUROSTAT/3D-SSP installations.   Please see the section below 'To use NEUROSTAT:  KEYCODE'.  A typical turnaround time for KEYCODE issuing is less than a week.

 

 

How to download NEUROSTAT/3D-SSP software

 

         1) 3D-SSP Windows version with Graphical User Interface (Diagnostic Z-score mapping)

 

         For those who are interested in 3D-SSP mapping of brain SPECT and PET imaging, you can use 3D-SSP software with Graphical User Interface (Windows) provided by Nihon Medi-Physics.  Please click here "Graphical User Interface".

 

 

         2) NEUROSTAT Command-line Software Library for MacOS, Windows Command Mode, and LINUX (Research Applications)

 

         For those who are interested in NEUROSTAT programs for command-line operations, please click below.  NEUROSTAT programs, including 3D-SSP, can be executed in a command line mode.  NEUROSTAT supports multiple computer platforms and operation systems.   To download NEUROSTAT, investigators need to download both ‘Program Files’ AND ‘Data Files’ (please see below).  Please click here "NEUROSTAT Command-line Software Library".

 

 

3D-SSP Graphical User Interface (Windows version)

 

         An English-version of graphical user interface (GUI) for 3D-SSP has been developed by Nihon Medi-Physics, Japan.  This English version runs on a Windows system and tested on Windows XP as well as older version of Windows systems.  We provide this GUI with various test normal databases (IMP, HMPAO, ECD, and, FDG).

 

         a) Please click here (3D-SSP GUI Download) to download the GUI with 3D-SSP programs and test databases.

        

         b) To install the GUI, 1) login as administrator; 2) place the downloaded zip file in the c:\Program Files directory and uncompressed (extract) files; 3) change properties (File->Properties) of the main folder (iSSP-NMP-us) and all the subfolders and filers to read/write/executable (uncheck all attributes and click ‘apply’).  Please note that if you are not using a standard Windows XP set up (e.g., if you cannot find c:\Program Files directory), you have to manually specific correct directory paths in the following files:

 

                  iSSP35.ini (main folder)

                  cnvttiff.prf (DocExec folder)

                  stereoSPECT.prf (DocExec folder)

                  stereoPET.prf (DocExec folder)

 

                  * Please note that installation on non-standalone workstations may require modifications of preference files.

 

         c) Please request a valid ‘KEYCODE’ (see above) and replace the old KEYCODE in the DocExec folder with a new one (either emailed or generated by ‘typekey’ command).

 

         d) Within the main folder, you will find 2 GUIs ‘iSSP35’ and ‘iSSP35_Viewer.exe’.   It is good to make shortcut for these 2 programs as well as folders ‘3DSSP-Input’ and ‘3DSSP-Output’ and place them on the Desktop.

 

         Please click ‘iSSP35.exe’ to start the GUI.  You can use a sample SPECT image in the folder “SampleSPECT” to test out the GUI.  You can find a draft user manual in the “Win_iSSP&Neurostat_Manual_PDF”. 

 

         This GUI can read directly DICOM volume files.  However, please note that PET (and MRI) DICOM files are often kept in multiple files of individual slices, instead of a single volume file (such as commonly used for SPECT DICOM format).  These PET image sets need to be converted to a single binary file (or DICOM volume file) prior to the analysis by the GUI.  Software, such as ImageJ (‘Import Image Sequence’), can perform this conversion.  By courtesy of Nihon Medi-Physics, Windows program ‘Scomb.exe’ is also provided to perform this conversion.  Please click here (‘Scomb.zip’) to download ‘Scomb.exe’ program and its documentation.

 

         If you succeed the installation and test run, you should see the following output (using iSSP35_Viewer) for visual interpretation of SPECT or PET images.

