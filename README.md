# Pruned-FFT
Fast Fourier Transform code (forward and inverse) for a pruned input sequence

Algorithm that takes the input array 'zr' of size N=2**m 
with 'kband' non-zero values starting from index 'kinit' 
and forward ('isign = 1') or inverse ('isign = -1') Fourier transforms it.
The N output samples are found in 'zr'

Number of complex multiplications is (N/2)log(2) kband
rather than                          (N/2)log(2) N

Written by:
Sverre Holm, Informasjonskontroll a.s, Asker, NORWAY 
Now at University of Oslo, Norway

ref:
S. Holm, "FFT Pruning Applied to Time Domain Interpolation and
Peak Localization", IEEE Trans. Acoust.,Speech, Sign. Proc.,
vol ASSP-35, pp. 1776-1778, Dec. 1987

Transposed version of:
K.Nagai,"Pruning the Decimatation-in-Time FFT Algorithm with Frequency
Shift", IEEE Trans. Acoust.,Speech, Sign. Proc., vol ASSP-34, Aug 198
