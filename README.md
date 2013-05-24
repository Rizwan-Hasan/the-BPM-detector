the-BPM-detector
================

Implementation of a Beats Per Minute (BPM) detection algorithm, as presented in the paper of G. Tzanetakis, G. Essl and P. Cook titled: "Audio Analysis using the Discrete Wavelet Transform". 

You can find it here: http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.63.5712

Usage

select the .wav file you want to analyze and pass it as an input argument in bpm_detection function as follows:

myfile = 'file.wav';
window = 3 # seconds
>> bpm_detection(myfile, window)

The above code should be executed in python's command line. 

Output

estBPM: the guess for the beats per minute

