
Advantages 
- noise tolerance
- constant envelop
Disadvantages
- more complex to describe
- bandwidth expansion

The phase can be acquired by

$\phi(t)=\begin{cases}k_{p}m(t),\text{for PM}\\2\pi \int_{-\infty}^{t}m(\tau)d\tau,\text{for FM}\end{cases}$

# Phase Modulation (PM)

$\phi(t)=k_{P}m(t)$

where $k_{p}$ is the modulation index. Message is in the phase

To acquire the maximum phase deviation 

$\Delta \phi_{max}=k_{p}max\mid m(t)\mid$ for PM
# Frequency Modulation (FM)

$f_{i}(t)=f_{c}+k_{f}m(t)$

where $k_{f}$ is the modulation index. Message is in the phase derivative

$m(t)=\frac{1}{2\pi}\phi^\prime(t)$ // unsure 

To acquire the maximum frequency deviation 

$\Delta f_{max}=k_{f}max\mid m(t)\mid$ for FM


## Transmission of FM,PM
The signal

$s(t)=A_{c}\cos(2\pi f_{c}t+\phi(t))$

the power can be found by

$P=\frac{A_{c}^2}{2}$

1. Precise Voltage-Controlled Oscillator (VCO)
	$\cos(2\pi f_{c}t+\phi(t))$ direct generation
2. Narrow-band FM/PM filter