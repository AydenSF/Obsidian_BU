---
tags:
  - ECED3201
loc: lect6
aliases:
  - Full-Wave Bridge Rectifier
---
This circuit crates a full wave rectification of a sinusoidal input


Bridge Rectifier:
![[Pasted image 20250220005152.png]]


The peak voltage ($V_{P}$) is the max $v_{s}$ the load could see.
if $v_{s}$ is [rms] then $V_{P}=V_{s}\cdot \sqrt{ 2 }$

The actual voltage is less than peak because of the diodes
$$V_{P}-2V_{D}$$
If the load has a filtering capacitor then the drop from peak to the next wave will be 
$$V_{P}-2V_{D}-V_{R}$$
