# xoscillo
Automatically exported from code.google.com/p/xoscillo
All credits go to Raul Aguaviva

A software oscilloscope that acquires data using an arduino or a parallax (more platforms to come).

###About
This is a multiplatform software oscilloscope and logical analyzer. It supports arduino(with custom firmware) and a [Parallax USB oscilloscope](http://www.parallax.com/Store/Microcontrollers/BASICStampProgrammingKits/tabid/136/ProductID/46/List/1/Default.aspx?SortField=ProductName,ProductName). More platforms to come.

###Features
* Panoramic view
* Load and save waveforms
* Zoom in and out
* Can open several waveforms at the same time
* Can run several oscilloscopes/logical analyzers simultaneously
* Frequency analysis using FFT
* Filtering, so far it has a low pass filter, probably more to come.
* Works on Windows and Linux (needs mono)
* Autodetects the hardware
* Post processing tools
  * Decodes fsk waves
  * Calculates wave main frequency using a few methods

##Supported platforms
* Arduino
* Parallax
* more to come... want to add your platform?

###Support
* Ask here in our [forum](http://groups.google.com/group/xoscillo/topics)

###Screenshots
* Basic screen shot showing the oscilloscope displaying a simple waveform
![XOscillo_time.png](images/XOscillo_time.png)
* Logic analyzer screenshot
![arduino-digital.png](images/arduino-digital.png)
* Displays the FFT of the signal and underneath the FFT over time.
![enhancedFFT.png](images/enhancedFFT.png)
* This screen shot shows an arduino based oscilloscope and a parallax one working simultaneously in realtime.
![arduino-parallax.png](images/arduino-parallax.png)
* Linux
![parallax_fft.png](images/parallax_fft.png)

###Notes from the Author
* The code is not by any means great, its just a quick exercise I did to learn c#.
* The program is not perfect but it works well enough though as to help many hobbyists in their small projects.
* The purpose of this project is to encourage others to contribute and improve the current code base.

###License
* http://creativecommons.org/licenses/by-nc-sa/3.0/
