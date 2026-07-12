# TELOCIDESI Ternary Simulator
Welcome ! This is the documentation for Telocidesi 0.1 DEV.

#### Licence
GNU GENERAL PUBLIC LICENSE, Version 3, 29 June 2007, see 'LICENCE' file

## Description
Telocidesi means Ternary Logic Circuit Designer & Simulator.<br>
As the name stands, this software is used to design and simulate the behaviour of logic circuits using ternary logic.

## USE
see original documentation /Doc/Use.html

## History

#### Inception
Telocidesi was developped for the 2nd year PIST Project in IMT Atlantique

The team :
- Grégoire CHAPEAUX<br>
- Louis DURET-ROBERT<br>
- Alexandre GEORJON<br>
- Yoan LEBLANC<br>
- Clément PRIME<br>
- Thomas ROUSSEAU<br>

#### Project
This project is a fork of https://github.com/Louis-DR/TelociDesi created by "Dr Louis and Co" circa 2019 <br>
Credit to Afif for partial recreation of the missing Config file, in fork https://github.com/afifafifafifafifali/TelociDesi


## Reference
https://louis-dr.github.io/telocidesi.html

Dr Louis has several ternary projects displayed online at https://louis-dr.github.io/index.html
<br><br>
## Changes made and planned
###Zero AI
Only human created, referenced and edited project, it might be bad but thats good.

#### Edited and added values to config file
    - need to / next
        - edit or quantify mystery numbers
#### Some gate and window colours changed to 'dark mode' pallet during testing
    - need to / next
        - finish replacing hex colours throughout code with variables
        - UI implement 'dark mode' button
        - UI colour selection
#### Added colour to inputs and outputs based on value
    - need to / next
        - UI improve visibility
        - UI improve selection/value change
#### Tags edited to label graph display
    - need to / next
        - more efficent code for graph display labels
        - add tag id and value to input/output/node/probe
        - UI imporve graph labeling
#### Window size adjusted for testing
    - need to / next
        - UI allow for resizeable window
        - UI resizeable or pop out toolbar
        - UI add navigation or scroll to main window
#### 3 input gate functionality added
    - need to / next
        - add more 3 input gate options ie any cons mul etc
        - UI add select number of inputs function
        - refacter code to allow for any number of inputs
        - add multiple output functionality for gates ie sum carry
#### Gates edited and added
    - fixed equation and value errors
    - added BUFF and NNOT gates
    - TRI input NAND and TRI input AND gates added
#### Mirror function edited to work for single selection
    - need to / next
        - fix mirror frame reference for select all


## To Do [original]
#### Bugs :
   - nodes and inputs can pass through gates if a wire hides the gate in screen
   - glitches with wires and nodes
   - knot circle on nodes between only two wires (should only be with 3 or more)
#### View modes :
   - unconnected nodes map : marks with a red square the nodes connected to nothing
   - too many output nodes map : marks with a red square output nodes connected together
   - connection mistakes map : marks with a red square nodes on wires without connection
   - node values
#### Wires :
   - auto-router around obstacles
   - bridge for wires crossing without connecting
#### Gates :
   - ability to mirror gates
   - negate output
   - finish other unary gates
   - basic gates with more than two inputs (AND, OR etc)
   - inprove the canPlace_gate function (redundant condition in the leftClick function ?)
#### Inputs and outputs :
   - easy inputs and outputs for naked system and gates inoutputs
#### Probes :
   - remove probes or fix them
#### Number input :
   - input a number with keyboard, outputs the signal on a given number of trits
#### Systems :
   - change the draw function so that systems show their orientation (dark corner, rounded corner, etc)
   - option for wide gaps between pins (1 or 2)
   - rotate and mirror
   - ability to display a value or information on it (register value, etc)
#### Memory :
   - double click to load new file
   - binary version
#### Register :
   - binary version
#### Simulation :
   - check if necessary to update node if already proper value
#### Logging and Visualisation :
   - separate software to visualize chronograms and output them to csv, excel, png, etc
#### User Interface :
   - clean the whole tool selection system....
   - replace text in buttons with icons
   - new panel and buttons for saving and loading
   - new panel and buttons for total cost
   - new panel for loading and placing systems
   - load a circuit corresponding to a system
   - reloading all system on the circuit (if their circuit changed) -> how to tackle the issue of changing number of inputs and outputs ?
#### Saving and Loading :
   - save simulation results
#### Undo Redo :
   - keep track of all changes : created/removed/moved/rotated gate/node/wire/input/prone/output, cut wire, negated gate
   - function to undo a change
#### Copy Paste :
   - copy the relative position, nature and relations of each item
   - ghost the size of the thing to paste
   - click to create each item then the relations (the wires)
#### Easy navigation :
   - panel to create, list and teleport to waypoints
#### Error handeling :
   - catch errors if save file is corrupted
   - catch errors if memory or system files don't exist anymore
