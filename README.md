# Debug-Code-List
A List Of Eboot &amp; Memory Patches To Enable The Debug Mode On Any PS4 Naughty Dog Game

Patch The .bin/.elf With The Hex Codes, OR Write [On 0x01] / [Off 0x00] To The Offset While The Game's Running. You Don't Need Both

(F; == Find | R; == Replace With)
_________________________________
### The Last of Us Remastered 1.00

Eboot Patch  
F; C6 87 81 2E 00 00 00  
R; C6 87 81 2E 00 00 01

Alternate Eboot Patch 0x5C79 0x01

Memory Edit 
0x114ED32E81
____________
### The Last of Us Remastered 1.09 to 1.11

Eboot Patch  
F; c6 87 81 2e 00 00 00  
R; c6 87 81 2e 00 00 01


Memory Edit
0x114F536E81
_____________
### The Last of Us Part II 1.00

Eboot Patch  
F; 31 c0 eb 49 4c  
R; b0 01 eb 49 4c


Memory Edit
0x110693FAA1
____________
### The Last of Us Part II 1.07 to 1.09

Eboot Patch  
F; 31 c0 eb 4c 4c  
R; b0 01 eb 4c 4c


Memory Edit
0x11069DFAA1
____________
### Uncharted: The Nathan Drake Collection

Eboot Patch (For All Three Games, Code's The Same. Apply To All Three Executables)  
F; 80 bf ba 39 00 00 00  
R; 80 bf ba 39 00 00 01
  
  
#### Uncharted 1 Memory Edits
Debug Menu: 0xD989CC | FPS Display: 0xD98970 | Task Display: 0xD97B41


#### Uncharted 2 Memory Edits
Debug Menus: 0x127149C | Task Display: 0x12705C9


#### Uncharted 3 Memory Edits
Debug Menus: 0x18366C4 | Task Display: 0x1835481
______________________________________________
### Uncharted 4 1.00

Eboot Patch  
F; c6 80 95 2e 00 00 00  
R; c6 80 95 2e 00 00 01

Memory Edit
0x1104FC2E95
____________
### Uncharted 4 1.32/1.33

Eboot Patch  
F; C6 80 79 2E 00 00 00 EB  
R; C6 80 79 2E 00 00 01 EB

Memory Edit
0x110491AE79
____________
### Uncharted 4 1.33 MP .elf 

Eboot Patch  
F; 79 2E 00 00 00 EB  
R; 79 2E 00 00 01 EB


Alternate Eboot Patch (0x1CCEB8 0x01)

Memory Edit: 0x1104B1AE79
____________________
### Uncharted 4 MP Beta 1.00

Eboot Patch (0x4C1B67 0x01)
___________________________
### Uncharted 4 MP Beta 1.09

Eboot Patch (0x4C1CD9 0x01)

Memory Edit 0x113408AE83 0x01
___________________________
### Uncharted: The Lost Legacy 1.00

Eboot Patch  
F; c6 80 f9 2e 00 00 00  
R; c6 80 f9 2e 00 00 01


Memory Edit
0x1105D1AEF9
____________
### Uncharted: The Lost Legacy 1.08/1.09

Eboot Patch  
F; c6 80 f9 2e 00 00 00  
R; c6 80 f9 2e 00 00 01


Memory Edit
0x1105D1AEF9
_____________

## Patches By TheMagicalBlob
