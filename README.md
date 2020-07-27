# TI-Terminal
TI-Terminal is a terminal interface for TI-83, 83+, and 84+ graphing calculators written in TI-BASIC.
It is entirely open source, so be sure to modify it and make new commands! Report bugs in this project's
forum thread on cemetech: https://www.cemetech.net/forum/viewtopic.php?p=286633

# In this repostiory:
CL_src1: The original source code for the list of commands.
CL_src2: The updated source code for the list of commands.
EXECLIB: A list the user will add programs they wish to execute from the terminal into.
For more info on how to insert programs, see Adding Programs.
README.md: The document you are reading now.
TERMINAL_Source_1.txt: The original terminal, on the Home Screen.
TERMINAL_src2: An updated terminal, moved to the Graph Screen.
TERMINAL_src_3: Final updated terminal. WARNING: MAY HAVE A LOT OF BUGS!
TERMINST_Source_1.txt: Original terminal installer.
TERMINST_src2: More recent terminal installer.
TERMINST_src3: Latest terminal installer.

# A list of commands

PRINT('STRING'): Prints a string of characters.
USRCHNG(NEW USERNAME): Changes username.
EXEC(PRGM): Executes a program specified by the user.
GET(KEY): Gets the value of the key pressed.
GET(PXL,X,Y): Gets the value of a pixel at desired location.
EXIT(): Exits the terminal.

# Adding programs

To add a program to the program list type this code into prgmEXECLIB where specified:
:If Str1="NAME OF PROGRAM GOES HERE":Then
:prgmRANDOM_PROGRAM_NAME          //or AsmPrgmSOME_PROGRAM_HERE for assembly programs
:ClrHome:ClrDraw
:End
