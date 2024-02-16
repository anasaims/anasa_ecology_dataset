# AIMS Bird Annotations Dataset

This repo is part of my ecology class at African Institute for Mathematical Sciences taught by Dr.Emmanuel Dufourq, Dr. Lorene Jeantet, Matthew Van den Berg, Milanto F. Rasolofohery.

## Data Collection

This data was collected using a Raspberry pi zero, in [Intaka Island](https://intaka.co.za/), Cape Town, SA. During 3 hours recorded from 8:30 AM to 11:30 AM across various locations across Intaka Island.

## File Structure

### Audios Directory
- `DD-MM-YYYY=HH_MM_SS.wav`: a timestamped wav file of a recording made using a raspberry pi zero
- `DDMMYY-HHMMSS.WAV`: a timestamped wav file recorded using a dual channel audiomoth
- `YYYYMMDD_HHMMSS.WAV`: a timestamped wav file recorded using another device

### Annotations Directory
- Each `*.wav` file has a corresponding `*.svl` file that has it's annotations, with `1` denoting presence and `0` denoting absence of bird vocalizations
- The `svl` file is the output of SonicVisualizer a well known app for annotating audio data, it follows an XML structure that is easily understandable

