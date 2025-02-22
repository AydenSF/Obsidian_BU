---
tags:
  - ECED3201
loc: lect8
aliases:
  - Hard Clipper
---

Hard limiters limit the output to a constant voltage.

For $$\frac{L_{-}}{K}\le v_{I} \le \frac{L_{+}}{K}$$
the limiter acts as a linear circuit $v_{o}=Kv_{I}$
If $K\gt 1$ there is amplification
If $K\lt 1$ there is attenuation
If $K=1$ $v_{o}=v_{I}$


Transfer characteristics
![[Pasted image 20250221164127.png]]

Applying a sine wave input can result in the peaks being clipped.

![[Pasted image 20250221164213.png]]

# Circuit Protection
Limiters are used to protect circuits from large voltages or spikes from electrostatic discharge.




# Hard Limiter Circuit Examples

## 1
![[Pasted image 20250221163956.png]]