# Hydrophone-Data
Project for B ME 450

https://github.com/neil-uwb/Hydrophone-Data/blob/master/Hydrophone%20Project.ipynb

Neil Skilton

Dr. Abadi

B ME 450

3/13/2020

# Intro 

The focus of this project is on understanding how acoustic data changes depending on what actions are taking place in and around a body of water. Using hydrophone data gathered from the Ocean Observation Initiative (OOI), I was able to build spectrograms of different situations in the water to see how they can be represented acoustically. Through this process, one would also learn how to read acoustic data and identify what is happening using the Wenz curve for reference.

# Data Collected:

The first major step of this process was to hunt down all of the data needed for each possible scenario. For this project, the focus was on wind, rain, earthquakes, animal sounds, and air guns. In order to avoid doing extra work, I sampled dates that were collected from the Meteorology Report. This gave me options for just wind, just rain, no wind and no rain, and both wind and rain at the Oregon Shelf Cabled Benthic Experiment Package (OSCBEP) and the Oregon Offshore Cabled Benthic Experiment Package (OOCBEP). 

Following the collection of this data, I needed to hunt down animal sounds, an earthquake, and air gun sounds. Fortunately, dates and times were provided for the animal sounds and the air gun sounds. In order to find an earthquake to use, I referred to the USGS site from our previous project to get an earthquake that was close to the arrays we were already sampling from for wind and rain data. Once compiled, I generated two plots for each set of data: one power spectral density (PDS) versus frequency plot and one spectrogram. Below is the data visualized by my code.

# OSCBEP Data:

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/1.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/2.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/3.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/4.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/5.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/6.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/7.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/8.png)

# OCBEP Data:

Note: Within the parameters set by my code in a previous project, there was no time without rain or wind

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/9.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/10.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/11.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/12.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/13.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/14.png)

# Earthquake Data:

Note: Adjusted the y_max since the earthquake was assumed to affect a range between 0-15 Hz.

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/15.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/16.png)

# Animal Call Data:

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/17.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/18.png)

# Air Gun Data: 

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/19.png)

![](https://github.com/neil-uwb/Hydrophone-Data/blob/master/21.png)

# Analysis

Looking at the wind and rain data, there is very little that changed in the spectrograms between the different weather patterns. I noticed that in the cases with a lot of wind, there appeared to be something happening between 250 and 500 Hz. Looking at the Wenz curve below, it appears that the anomalies are nothing more than basic ocean traffic since they appear to be within 20 dB and under 500 Hz. Aside from those few anomalies, there is very little to distinguish between the rain and wind using the acoustic data gathered. This may be due to the parameters that I have set. With different parameters, there is a chance that I could get better acoustic data.

![]()

From the little information that is available, it appears that rain has a larger impact based on the PSD graphs of just wind and just rain. The difference between the two locations may come down to the depth that the hydrophone is placed at. The depth can affect how easily surface level actions reach the hydrophone, which may put the hydrophone that is in shallower waters at an advantage.

The data found for the earthquake, animal, and air gun was significantly more pronounced. An animal call was clearly visible between 2000 Hz and 3000 Hz for around one second. On the air gun data, there appeared to be large signals every 10 seconds that span a very large bandwidth, with smaller signals every 5 seconds that span a smaller bandwidth. The earthquake data is really interesting, with drop in the dominant frequency, which I am assuming is the time in between the initial earthquake and aftershocks.

# Conclusion:

Given the data above, it appears that rain has the most impact, in terms of surface level regular weather. Using a Wenz curve, one can easily identify the type of sound that is being recorded, and with multiple forms of visual analysis, can accurately describe the sound source. Overall underwater acoustics appears to be a very powerful tool and I look forward to learning more about it.

# References:

[1]	    Abadi, S (2020). Lecture 6_Ocean Noise. [online] University of Washington Bothell [Accessed 13 March. 2020]
[2]	    Abadi, S (2020). Hydrophone Project. [online] University of Washington Bothell [Accessed 13 March. 2020]

