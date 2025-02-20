---
tags:
  - demodulation
---
inverse process to [[Modulation]] 


# Demodulation Checks
Quick checks that can be done to figure out viable demodulation types


## Envelope Detector Check
To be demodulated via envelope detector

$m(t)\gt0,\forall t$ 

### Examples

1. $m(t)=2+\sin(t)$
	$-1\le \sin(t)\le 1\rightarrow 1\le m(t)\le 3$
	Because $m(t)$ is always positive it can be demodulated using an envelope detector 
2. $m(t)=\cos(t)$ 
	$-1\le \cos(t)\le 1\rightarrow -1\le m(t)\le 1$
	Because $m(t)$ is negative for some time it must be demodulated using a coherent receiver 

