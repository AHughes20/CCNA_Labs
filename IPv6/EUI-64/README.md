# Examining EUI-64

## Topology
<img width="597" height="292" alt="IPv6_EUI-64_Lab" src="https://github.com/user-attachments/assets/3ee51070-8bbf-4c32-a756-fac553298e7b" />


## Objectives
- This lab will show the results of EUI-64 when setting an IPv6 address on an interface causing it to obtain a link-local using EUI-64 process.
- You can also use EUI-64 for you IPv6 unique local addressing, which is what I used on g0/0 int. g0/0/0 was set using a chosen IPv6 address.
- Notice the first 4 hex values of the link-local address. FE80::/10 is the IPv6 link-local prefix.

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

