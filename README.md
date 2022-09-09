# Voice-Signal-Processing-using-Matlab

- ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `Abstract ` 

Here we will proceed to record 3 distinct voices.Two male and one
female. Then we will pass them through a lowpass filter. After that these
recordings will be modulated , it is to be noted that each of the recordings will be
modulated using carrier signals of varying frequency. After that they will be sent
through a common channel. The recordings will then be passed through a band
pass filter and demodulated afterwards.Soon after the original messege signal
which is the initial voice recording will be reconstructed.

- ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `Methodology `

![#c5f015](https://via.placeholder.com/15/c5f015/c5f015.png) `Voice Massage Input`

In our project, we have taken 3 different voice records. Those voice
recordings are converted in to massage signals through MATLAB. Each
voice has different frequency ranges. As we know male and female voices
have different frequency ranges (female voice is sharper than male voice),
the input massages that we took can’t be of the same frequency. In our
project, we took two male voice records and one female voice record.

![#c5f015](https://via.placeholder.com/15/c5f015/c5f015.png) `Low Pass Filter`

After taking the input massage signal, we put those signals through low pass
filter to eliminate the unwanted over noise and have the signals in range.
Here, the frequency range we took was from 3.3kHz to 3.7kHz

![#c5f015](https://via.placeholder.com/15/c5f015/c5f015.png) `Carrier signals`

To have this transmission, three different carrier signals have been taken. All
of them have different frequency range. Those carrier signals are 1MHz
,4MHz and 8MHz

![#c5f015](https://via.placeholder.com/15/c5f015/c5f015.png) `Modulation`

In the modulator the modulation has been done for each signal. Three signals
have been modulated with three different carriers. After the modulation themodulator generates a modulated signal and the output signal carries the
carrier’s frequency with the massage signal

![#c5f015](https://via.placeholder.com/15/c5f015/c5f015.png) `Multiplexing`

All the signals are combined together for the transmission in this
multiplexing stage. As the three different modulated signals will be
transmitted at a time, they make a packet by multiplexing. Suppose the three
modulated signals are


- ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `Conclusion `

I n conclusion the assignment was completed successfully. This particular problem
had several key steps modulating, demodulating and reconstructing. Also we had
to work with audio files. Completing all these steps required hundreds of lines of
MATLAB code. After completing it, the first few times the code didn't run the
way it was supposed to. So we had check for errors. After going through the code a
few times we ran it again this time we changed a few things. At first we tried using
6 second recordings and we were unsuccessful. Then we extended the size of the
recordings to 10 seconds and that seemed to be the answer. After sorting that out
that we observed that there was still some noise in the output. We fixed that using
another Low pass filter. And finally in order to get a clear output we had to adjust
the gain properly. All in all the problem was somewhat challenging but we got the
job done in the end.
