# Frequency_Domain_Examples

Here are simple examples on for to transform time domain data into frequency domain with  Fourier Transform.

The frequency domain is an analysis method used to study the same signals or systems in terms of frequency
instead of time. This transformation from the time domain to the frequency domain is achieved through
mathematical tools like the Fourier Transform. In the frequency domain, signals are expressed in terms
of sinewaves and their frequencies. Analysing signals in this domain allows one to observe the periodic
structures within the data, identify the dominant frequencies present, and understand how different frequency components contribute to the signal's behaviour. It is instrumental in hydrology when studying (seasonal) water flow or temperature fluctuations.

The Fourier Transform is a mathematical transformation used to convert a function of time (or space) into a
function of frequency. The equation for the Fourier Transform F(ω) of a continuous time-domain signal f(t):

F(ω)=∫_(-∞)^∞▒〖f(t) e^(-iωt) dt〗

Where F(ω) is the Fourier Transform of a function, f(t) - the original time-domain function, ω is the angular frequency in radians per second, i is the imaginary unit, √-1. The integral is evaluated over time from −∞ to +∞. The result, F(ω), is generally a complex function where the magnitude represents the amplitude of the frequency component, and the argument (or phase) represents the phase shift of the frequency component.
