# Link-Local Gotcha Lab

## Topology
<img width="625" height="398" alt="Link_Local_Gotcha" src="https://github.com/user-attachments/assets/63833f05-3be0-48f0-8a2e-6ecceb29d964" />


## Objectives
- This lab will show what happens if you set the local router's link-local address as the next hop.
- You will notice Cisco accepts the address with no indication of trouble. You will also see that a static route will be added to the IPv6 routing table
  that appears to be valid.

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
