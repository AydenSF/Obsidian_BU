---
tags:
  - ECED3511
loc: lect2
aliases:
  - Trigonometric Fourier Series Coefficients
---



$$x(t)=\frac{a_{0}}{2}+\sum_{n=1}^{\infty}\left[ a_{n}\cos\left( n \frac{2\pi}{T_{0}}t \right)+b_{n}\sin\left( n \frac{2\pi}{T_{0}}t \right) \right]$$
$w_{0}=\frac{2\pi}{T_{0}}$, is the fundamental angular frequency 
$T_{0}$ is the [[Fundamental Period]] 

Where $$a_{0}=\frac{1}{T_{0}}\int_{T_{0}}x(t)dt$$
$$a_{n}=\frac{2}{T_{0}}\int_{T_{0}}x(t)\cos\left( n \frac{2\pi}{T_{0}} \right)dt$$
$$b_{n}=\frac{2}{T_{0}}\int_{T_{0}}x(t)\sin\left( n \frac{2\pi}{T_{0}} \right)dt$$
