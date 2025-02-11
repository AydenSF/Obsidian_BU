---
tags:
  - signals
  - signal_modulation
description: Explains the different forms of modulation.
---
Also see [[Demodulation]]
# Frequently Used Functions and Definitions

$m(t)$ // this is a message signal
$c(t)$ // this is the carrier signal

terms
- Double Side Band (DSB)
- Single Side Band (SSB)
- Suppressed Carrier (SC)

# Conventional Amplitude Modulation (AM)

Conventional AM is a DSB signal with the a transmitted carrier. This means the signal is transmitted with a copy of the carrier.

$s(t)=A_{c}\cdot m(t)\cdot c(t)+c(t)\cdot A_{c}$ 

can also be written as 

$s(t)=A_{c}[1+m(t)]c(t)$ 

where 

$c(t)=\cos(2\pi f_{c}t+\phi_{t})$ 

If $m(t)\gt 1$ for some t the signal must be normalized. As to keep the envelop above 0. // explain envelop somewhere 

$m_{n}(t)=\frac{m(t)}{max\mid m(t)\mid}$

$s(t)=A_{c}[1+am_{n}(t)]c(t)$ 

$a$ is the modulation index it is selected such that

$m_{n}(t)\cdot a+1\ge 0$


# Angle Modulation
Advantages 
- noise tolerance
- constant envelop
Disadvantages
- more complex to describe
- bandwidth expansion

The phase can be acquired by

$\phi(t)=\begin{cases}k_{p}m(t),\text{for PM}\\2\pi \int_{-\infty}^{t}m(\tau)d\tau,\text{for FM}\end{cases}$

## Phase Modulation (PM)

$\phi(t)=k_{P}m(t)$

where $k_{p}$ is the modulation index. Message is in the phase

To acquire the maximum phase deviation 

$\Delta \phi_{max}=k_{p}max\mid m(t)\mid$ for PM
## Frequency Modulation (FM)

$f_{i}(t)=f_{c}+k_{f}m(t)$

where $k_{f}$ is the modulation index. Message is in the phase derivative

$m(t)=\frac{1}{2\pi}\phi^\prime(t)$ // unsure 

To acquire the maximum frequency deviation 

$\Delta f_{max}=k_{f}max\mid m(t)\mid$ for FM

## Carson's Rule

The bandwidth of the message signal is $\omega$. $B_{c}$ is the effective bandwidth of the modulated signal.

$B_{c}=2(\beta+1)\omega$
$\frac{}{}$
where

$\beta=\begin{cases}k_{p}max\mid{m(t)\mid},\text{for PM}\\k_{f}\frac{max\mid m(t)\mid}{\omega},\text{for FM}\end{cases}$

![[Pasted image 20250211003420.png]]

## Transmission of FM,PM
The signal

$s(t)=A_{c}\cos(2\pi f_{c}t+\phi(t))$

the power can be found by

$P=\frac{A_{c}^2}{2}$

1. Precise Voltage-Controlled Oscillator (VCO)
	$\cos(2\pi f_{c}t+\phi(t))$ direct generation
2. Narrow-band FM/PM filter