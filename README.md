# Voice-Signal-Processing-using-Matlab

Abstract: Here we will proceed to record 3 distinct voices.Two male and one
female. Then we will pass them through a lowpass filter. After that these
recordings will be modulated , it is to be noted that each of the recordings will be
modulated using carrier signals of varying frequency. After that they will be sent
through a common channel. The recordings will then be passed through a band
pass filter and demodulated afterwards.Soon after the original messege signal
which is the initial voice recording will be reconstructed.




Methodology 
Voice Massage Input:
In our project, we have taken 3 different voice records. Those voice
recordings are converted in to massage signals through MATLAB. Each
voice has different frequency ranges. As we know male and female voices
have different frequency ranges (female voice is sharper than male voice),
the input massages that we took can’t be of the same frequency. In our
project, we took two male voice records and one female voice record.

Low Pass Filter:
After taking the input massage signal, we put those signals through low pass
filter to eliminate the unwanted over noise and have the signals in range.
Here, the frequency range we took was from 3.3kHz to 3.7kHz

Carrier signals:
To have this transmission, three different carrier signals have been taken. All
of them have different frequency range. Those carrier signals are 1MHz
,4MHz and 8MHz

 Modulation:
In the modulator the modulation has been done for each signal. Three signals
have been modulated with three different carriers. After the modulation themodulator generates a modulated signal and the output signal carries the
carrier’s frequency with the massage signal

Multiplexing:
All the signals are combined together for the transmission in this
multiplexing stage. As the three different modulated signals will be
transmitted at a time, they make a packet by multiplexing. Suppose the three
modulated signals are,
