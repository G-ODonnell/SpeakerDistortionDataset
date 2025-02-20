# SpeakerDistortionDataset
A speaker distortion dataset for the purposes of machine learning.

Description
--

The purpose of the experiment was to record a set of speaker responses to demonstrate the ability to extract information from non-linear conditions.
The speaker was prepared by removing the crossover circuit and leaving the speaker port open.
A 90 Hz square wave was played through the speaker using a 1600W Yorkville Class H amplifier, measuring at approximately 100 dBA.
The response was captured with the use of a Shure SM-57. The microphone was in motion in the radial direction during the capture, it took approximately 90 seconds for the microphone to travel from edge to edge with the 6.5" speaker.
Motion was controlled by a Dynamount X2-R, with addition shock protection.
Speaker's DC Resistance meaasured at 6.98 Ohms, beginning axial distance from speaker edge to microphone diaphragm is 2 inches.
Speaker make and model is a Tannoy 605.

Positions (Scaled by Inverse Square Law)
--
1 - 2"

2 - 7.9"

3 - 12"

4 - 14.9"

5 - 17"

Trials
--
1 - Anechoic Conditions

2 - Non-Anechoic Conditions

Loads
--
1 - No added resistance

2 - 1.5 ohm series resistance

3 - 3 ohm series resistance

Recording information
--
Sampling Rate: 96,000 Hz

Number of Channels: 1

Original Bit Depth (Prior to pre-processing): 24 bit

Window Size: 1067 samples

--
Pre-processing information
--
As the speaker time distortion is the information-dense part of the captures, no equalization was used. 
High-pass filtering is _not_ recommended.

Window start points begin at positive inflection points conditional to a threshold close to the mean of the signal.
Each window should show a single cycle of a square wave response.
Since the microphone is moving during the capture, each cycle represents a unique datapoint.


