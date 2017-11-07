# ibt_beat_tracking
A beat tracking external for MaxMSP.  

Original source codes and project files are taken from: https://github.com/marsyas/marsyas/tree/master/src/marsyas_max-msp


How to compile
- Install Marsyas: https://github.com/marsyas/marsyas/
	- In order to install Marsyas, you need Qt5: http://qt.io/
	- Configure Marsyas compilation in cmake-gui
     Enable: WITH_MAX/MSP and MARSYAS_STATIC 
     Disable:  WITH_MATLAB (if you don't have MATLAB installed) 
