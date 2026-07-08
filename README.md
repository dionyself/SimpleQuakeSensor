# Simple Quake Sensor 
SimpleQuake Sensor is an Earthquake Analyzer. (Work in Progress)  
Useful to capture and analyze Natural EM wave emitions and Earthquake EM emitions.  
The circuit works as an electronic ear that works as a broadband receiver  

### Primary EM waves 0 - 40 Hz  
- Ultra Low Frequency: f < 3 Hz  
- Extremely Low Frequency: 3 Hz < f < 3 kHz  
- Very Low Frequency: 3 kHz < f < 30 kHz  

### Secundary Emitions  30 kHz - 5.8 gHz  
- High Frequency: 3 MHz < f < 30 MHz  
- Very High Frequency: 30 MHz < f < 300 MHz    

### Real PCB View (from Kicad 3D viewer)
![Real World View.](/Images/SimpleQuakeSensorView.png)

## How to use it?

1 - Assembly the device  (gerber files provided <here>)  
2 - Connect your devide to your audio analizer / pc using this <> cable  
3 - Connect your devices input to ground using 2 probes + good coaxial <example>  
4 - Take audio samples as you like: `parec raw_sample.raw --file-format=raw` ( Linux command )  
              or    
5 - Use your favorite Audio analizer to listen and view the live data `jaaa -A -d hw:1`  

### My Results

I have included images, screenshoots and audio files captured during relevant events:  

a) 0 - 1.5 kHz

![First Natural Capture.](/Images/natural_capture.png)