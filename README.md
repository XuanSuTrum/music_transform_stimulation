# music_transform_stimulation  
This repository discribe how to transform the music into stimulation signals.  
It has severals steps:  
1）Time-frequency information: librosa Library converts music audio information into time-frequency information;  
2) The frequency value with the strongest energy at each time point is extracted according to the time order of the information, and the corresponding frequency energy value is recorded.  
3) The pre-established correspondence between pitch and frequency is obtained, and the time pitch data of each time point in the music is obtained according to the increasing or decreasing order of pitch and the set frequency of each electrical stimulation The lower limit interval forms a one-to-one correspondence.  
4) The continuous and identical pitch data in the music playing time point are combined into one tone, and the duration of each tone is calculated according to the playing time order, and the data of the time pitch length is obtained.  
5) The energy value of each frequency is averaged according to the length of the tone, and the loudness characteristics of each tone are obtained
