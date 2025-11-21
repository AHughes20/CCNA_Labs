# Bridge Priority Lab

## Topology
<img width="785" height="371" alt="BridgePriorityLab" src="https://github.com/user-attachments/assets/0e070406-1cdb-4884-b5d4-1783a70c995f" />


## Objectives
- In this lab I change the bridge priority for vlan 1, setting SW4 as primary root, which will set the bridge priority to 24576 or 4096 lower than current root (In this topology all switches are default priority of 32768) causing the switch to become the new root bridge for vlan 1
- Observe how root bridge begins as SW5, but after setting SW4 as root primary, soon begins its new status as root bridge. 

## Setup
- All switches are preconfigured with only a hostname and rapid-pvst enabled.
- There is one single gigabit link in the topology between SW3 and SW5 to be aware of.

## Steps Performed
Short list of what was done in the lab.  
(Keep this high-level. Details go in configs.)

## Verification
Include the important `show` commands you captured:
- `show spanning-tree`
- `show spanning-tree root`
- Anything that proves the concept.

## Expected Behavior
Describe what *should* happen and why the result makes sense.

## Files Included
- `configs/` – device configs  
- `outputs/` – command-output text files  
- `topology.png` – diagram  
