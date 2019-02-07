# tfw_editor_bokeh
tool for editing Agilent tfw files.  Includes bokeh interactive tools

Files:

-tfw_readwrite_bokey.ipynb:  jupyter file which can be opened in Google Colaboratory
-ShootThroughSetup.TFS: Setup file for Agilent function generator.  Sets time and amplitude scales.  Warning: You must
  "recall" this file in your function generator before enabling the output else 1kHz default waveform will be applied 
  to your SPS PWM  which will consequently experience rapid exothermic expansion.
-tfw_files - these are the files you will load into the agilent function generator as "arbitrary waveforms"
-tfwlib.py - library of functions to read and write tfw files.  
