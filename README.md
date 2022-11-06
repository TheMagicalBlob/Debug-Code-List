# Debug-Code-List
A List Of Eboot &amp; Memory Patches To Enable The Debug Mode On Any PS4 Naughty Dog Game

Naughty Dog Debug "Codes" / Offsets

Patch The .bin/.elf With The Hex Codes, OR Write [On 0x01] / [Off 0x00] To The Offset While The Game's Running. You Don't Need Both

(F; == Find | R; == Replace With)
---------------------------------
The Last of Us Remastered 1.00

Eboot Patch
F; C6 87 81 2E 00 00 00
R; C6 87 81 2E 00 00 01

Memory Edit
0x114ED32E81
------------
The Last of Us Remastered 1.09 to 1.11

Eboot Patch
F; c6 87 81 2e 00 00 00
R; c6 87 81 2e 00 00 01

Memory Edit
0x114F536E81
-------------
The Last of Us Part II 1.00

Eboot Patch
F; 31 c0 eb 49 4c
R; b0 01 eb 49 4c

Memory Edit
0x110693FAA1
------------
The Last of Us Part II 1.07 to 1.09

Eboot Patch
F; 31 c0 eb 4c 4c
R; b0 01 eb 4c 4c

Memory Edit
0x11069DFAA1
------------
Uncharted: The Nathan Drake Collection

Eboot Patch (All Three Games, Code's The Same. Apply To All Three Executables)
F; 80 bf ba 39 00 00 00
R; 80 bf ba 39 00 00 01

Memory Edit

Uncharted 1
Debug Menu: 0xD989CC|FPS Display: 0xD98970|Task Display: 0xD97B41
-
Uncharted 2
Debug Menus: 0x127149C|Task Display: 0x12705C9
-
Uncharted 3
Debug Menus: 0x18366C4|Task Display: 0x1835481
----------------------------------------------
Uncharted 4 1.00

Eboot Patch
F; c6 80 95 2e 00 00 00
R; c6 80 95 2e 00 00 01

Memory Edit
0x1104FC2E95
------------
Uncharted 4 1.32/1.33

Eboot Patch
F; C6 80 79 2E 00 00 00 EB
R; C6 80 79 2E 00 00 01 EB

Memory Edit
0x110491AE79
------------
Uncharted 4 1.33 MP .elf 

Eboot Patch (0x1CCEB8 0x01)

F; 79 2E 00 00 00 EB
R; 79 2E 00 00 01 EB

Memory Edit: 0x1104B1AE79
--------------------
Uncharted 4 MP Beta 1.00

Eboot Patch (0x4C1B67 0x01)
---------------------------
Uncharted 4 MP Beta 1.09

Eboot Patch (0x4C1CD9 0x01)

Memory Edit 0x113408AE83 0x01
---------------------------
Uncharted: The Lost Legacy 1.00

Eboot Patch
F; c6 80 f9 2e 00 00 00
R; c6 80 f9 2e 00 00 01

Memory Edit
0x1105D1AEF9
------------
Uncharted: The Lost Legacy 1.08/1.09

Eboot Patch
F; c6 80 f9 2e 00 00 00
R; c6 80 f9 2e 00 00 01

Memory Edit
0x1105D1AEF9

All Patches By TheMagicalBlob
