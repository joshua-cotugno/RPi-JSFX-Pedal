# Raspberry Pi based JSFX Controller

### _Computer Science A Level Project_
## Basic Idea
To create a Guitar pedal with a web-based interface for a Raspberry Pi.
- Effects would be coded in JSFX
- Cross-Platform
- Effects can be arranged in the interface, added to (_and removed from_) database via upload, and browsing interface
- Can be assigned physical buttons on a USB keyboard, or hardware buttons to turn on/off effects
- Effect's values can be edited using interface (_and also toggled on/off_)
<br>
<iframe frameborder="0" style="width:100%;height:594px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Basic%20Layout.drawio#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fjoshua-cotugno%2FRPi-JSFX-Pedal%2Fmain%2FBasic%2520Layout.drawio">Not Supported In this Browser/Viewer</iframe>
**_Figure 1: Basic Layout Diagram_**
_Above_

****
<br>

## Basic File Layout Plan:

### Frontend:
* index.html
* upload.html
* ( _script.js, styles.css_ )

### Backend:
Either `Node.js` or Python `Flask` with EEL2

****

## Basic Algorithm for System
1. JSFX sent to device
2. JSFX added to effects queue under a if loop
3. UI Updates with 