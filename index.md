Hello World
# Basics

## Convolution



# Design of Digital Filters

## Selection of filter type
```
If linear-phase required within the passband:
  use FIR
else:
  If fewer parameters (less memory) desired:
    use IIR
  else:
    use FIR
```

* linear-phase requirement is generally true in telecommunication where signal need to be demodulated without distortion

## Frequency transformation

Transform a lowpass prototype filter into another lowpass, bandpass, bandstop, or highpass filter

## Conditions imposed by casuality

1. the frequency response H(w) cannot be zero, except at a finite set of points in frequency
2. the magnitude |H(w)| cannot be constant in any finite range of frequencies and the transition from passband to stopband cannot be infinitely sharp
3. the real and imaginary parts of H(w) are interdependent and are related by the discrete Hilbert transform.

