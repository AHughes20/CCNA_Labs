# Examining DHCP Snooping and DAI

## Topology
Brief description of the topology and purpose of the lab.  
(Include `topology.png` here if you have one.)

## Objectives
- Enable DHCP Snooping on VLAN 10.
- Configure trusted/untrusted ports for DHCP traffic.
- View DHCP Snooping binding table.
- Enable DAI and validate ARP packets using the DHCP binding table.
- Observe behavior when a rogue DHCP server or invalid ARP packet is introduced.

## Setup
- Switch models / software versions.
- Any special interface notes (duplex changes, cost changes, etc).

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
