****************************************
Turntable Rumble Indicator
****************************************
JSFX Plugin for Reaper DAW to measure the "rumble" of a turntable via a record-armed track.

TRI measures rumble according to standard IEC 60098 "analogue audio disk records and reproducing equipment" (aka IEC98). 
Turntable rumble essentially is a audioband noise measurement with a frequency and time weighting applied. 
The relevant standard (IEC98) changed 1987: Frequency and time weighting characteristics were adjusted. 
This JSFX plugin can be set to measure according to deprecated and current characteristics.

_____ IEC98:1964 (unweighted / A-curve) ________

Deprecated measurement method. Most turntables were designed during the time period when this standard was valid. If one wants to check, 
if a turntable designed before 1987 conforms to the manufacturers specifications, use this setting.

FREQUENCY weighting - turnover frequencies 10Hz (low-pass roll-off 6dB/oct) and 315Hz (high-pass roll-off of 12dB/oct) 

TIME weighting - ANSI C16.5.1954 standard VU meter characteristic with 3 seconds rise/decay time


_____ IEC98:1987 (unweighted / X-curve) ________

Current measurement method. Measurments with this setting are in accordance with the valid turntable measurement standard IEC 60098:1987, which references IEC61672 for the time weighting characteristic.

FREQUENCY weighting - turnover frequencies 20Hz (low-pass roll-off 18dB/oct) and 315Hz (high-pass roll-off of 12dB/oct) 

TIME weighting - "slow"/"S" characteristic found in IEC61672 "sound level meter" under paragraph 5.8 "time weightings F and S". 
Represents a RMS-meter with a time constant of 1s and a decay-rate of 34,7dB/sec.


_____ IEC98:1964 (weighted / B-curve) _______________

The measurement method for "weighted rumble" according to standard before 1987.

FREQUENCY weighting - low-pass and high-pass roll-off each with 12dB/oct around 315Hz center frequency

TIME weighting - ANSI C16.5.1954 standard VU meter characteristic with 3 seconds rise/decay time


_____ IEC98:1987 (weighted / Y-curve) _______________

The measurement method for "weighted rumble" according to standard after 1987.

FREQUENCY weighting - low-pass and high-pass roll-off each with 12dB/oct around 315Hz center frequency

TIME weighting - "slow"/"S" characteristic found in IEC61672 "sound level meter" under paragraph 5.8 "time weightings F and S". 
Represents a RMS-meter with a time constant of 1s and a decay-rate of 34,7dB/sec.


_____ 20Hz turnover / fast (1987) ___________

Use this setting, if you want faster meter response. For example if you want to use TRI as an aid during turntable setup.

FREQUENCY weighting - turnover frequencies 20Hz (low-pass roll-off 18dB/oct) and 315Hz (high-pass roll-off of 12dB/oct) 

TIME weighting - ANSI C16.5.1954 standard VU meter characteristic with 300 milliseconds rise/decay time

_____ 10Hz turnover / VU 300ms (1964) ___________

Use this setting, if you want faster meter response. For example if you want to use TRI as an aid during turntable setup.

FREQUENCY weighting - turnover frequencies 10Hz (low-pass roll-off 6dB/oct) and 315Hz (high-pass roll-off of 12dB/oct) 

TIME weighting - ANSI C16.5.1954 standard VU meter characteristic with 300 milliseconds rise/decay time

_____ flat / VU 300ms ___________

Basically a standard VU meter. No FREQUENCY weighting is applied, 300ms rise/decay time.




