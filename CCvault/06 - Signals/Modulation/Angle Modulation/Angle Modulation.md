---
tags:
  - ECED3511
loc: lect7
---

Advantages 
- noise tolerance
- constant envelop
Disadvantages
- more complex to describe
- bandwidth expansion

There are two types [[Phase Modulation (PM)]] and [[Frequency Modulation (FM)]]

The phase is a function of the [[Message Signal]].

$$\phi(t)=\begin{cases}k_{p}m(t),\text{for PM}\\2\pi \int_{-\infty}^{t}m(\tau)d\tau,\text{for FM}\end{cases}$$
$$\phi\prime(t)=\begin{cases} k_{p}m\prime(t)\\k_{f}2\pi m(t) \end{cases}$$


# Transmission of FM,PM
The signal

$s(t)=A_{c}\cos(2\pi f_{c}t+\phi(t))$

the power can be found by

$$P=\frac{A_{c}^2}{2}$$

1. Precise Voltage-Controlled Oscillator (VCO)
	$\cos(2\pi f_{c}t+\phi(t))$ direct generation
2. Narrow-band FM/PM filter