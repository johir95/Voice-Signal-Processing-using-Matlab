# Voice-Signal-Processing-using-Matlab

- ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `Abstract ` 

This project encompasses the modulation, transmission, and demodulation of three distinct voice recordings through a common channel. Initially, the voice recordings are converted into message signals, filtered through a low pass filter, and modulated with carrier signals of varying frequencies. These modulated signals are multiplexed for transmission and subsequently passed through a band pass filter for demodulation. Through demodulation, the original message signals are reconstructed. The project involved extensive MATLAB coding and troubleshooting to address issues such as signal noise and modulation clarity. Despite challenges, the project successfully achieved its objectives, demonstrating effective modulation and demodulation techniques for voice transmission.

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

![111111111111](https://user-images.githubusercontent.com/90377555/189332527-b54cc94a-2230-45c2-8c29-e594bee1d1f3.jpg)


![#c5f015](https://via.placeholder.com/15/c5f015/c5f015.png) `Band Pass Filter`

After the transmission, the multiplexed signal will go through the band pass
filter. This process will work like a demultiplexing process. In this stage, the
signal having three massages gets separated from each other by the band pass
filter. As we know the signals have different frequency ranges so that theyare not mixed together. And in between the massages of these signals, there
is a guard band. This guard band stops the three massage signals from mixing
up. Usually for the transmission, the guard band is of (300+600)
kHz=900kHz range.



![#c5f015](https://via.placeholder.com/15/c5f015/c5f015.png) `Demodulator`

The separated signals that we got after the demultiplexing stage they are not
quiet the massage signals. To get the actual massage signal, demodulation
have been done. By demodulating the carriers have been removed and
demodulator’s output is more likely to the massage signals. The signals we
get from here are the reconstructed signals of our massage signal. With
MATLAB, we get to convert these massages into voice massage again to
hear the massage signals in the receiver side


![22222222](https://user-images.githubusercontent.com/90377555/189333391-4062f0d2-3d6c-4609-9ea9-a71a198960f1.jpg)





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
