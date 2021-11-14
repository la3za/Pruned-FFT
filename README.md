# Pruned FFT
Fast Fourier Transform code for a pruned input sequence to accompany the paper  S. Holm, ["FFT Pruning Applied to Time Domain Interpolation and
Peak Localization"](https://www.researchgate.net/publication/3178273_Fft_Pruning_Applied_to_Time_Domain_Interpolation_and_Peak_Localization), IEEE Trans. Acoust.,Speech, Sign. Proc., vol ASSP-35, pp. 1776-1778, Dec. 1987

Algorithm that takes the input array 'zr' of size N=2**m 
with 'kband' non-zero values starting from index 'kinit' 
and forward ('isign = 1') or inverse ('isign = -1') Fourier transforms it.
The N output samples are found in 'zr'

Number of complex multiplications is (N/2)log(2) kband
rather than                          (N/2)log(2) N

Written by:
Sverre Holm, Informasjonskontroll a.s, Asker, NORWAY. 
Now at University of Oslo, Norway
