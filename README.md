****************************************
Turntable Rumble Indicator
****************************************
JSFX Plugin for Reaper DAW to measure the "rumble" of a turntable.

Turntable rumble essentially is the result of an audioband noise measurement with a frequency weighting towards the lower part of the audio frequency spectrum. The Turntable Rumble Indicator (tri) can, in combination with Reaper DAW and a decent AD-converter, measure rumble according to the standard IEC98 "analogue audio disk records and reproducing equipment". There are two relevant versions of this standard: the old IEC 60098:1964 (superseded 1987) and the new IEC 60098:1987 (valid today). In 1987 the frequency weighting characteristics for the measurement was adjusted. The response characteristic (time weighting) of the meter indication was also adjusted 1987. Both are explained below. Often the German DIN 45539:1981 is specified, this is the same as the old version of IEC98 and also got superseded 1987 by the new IEC98.

Frequency weighting: 
There are two measurement modes specified: weighted and unweighted. 
Weighted: Old and new versions of IEC98 require a filter centered at 315Hz and falling of with 12dB/oct each side.
Unweighted: At high frequencies old and new versions of IEC98 specify that the filter should be limited at 315Hz with 12dB/oct. Before 1987 frequencies from 10Hz (with a roll-off of 12dB/oct below that) up to 315Hz were accounted by rumble measurement. After 1987 only frequencies from 20Hz (with a roll-off of 18dB/oct below that) up to 315Hz were accounted by rumble measurement.

Time weighting (meter response characteristic):








