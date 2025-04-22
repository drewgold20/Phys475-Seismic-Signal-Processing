# Phys475-Seismic-Signal-Processing
Seismic signal processing project using FFT and wavelet transforms to analyze real earthquake data. FFT reveals dominant frequencies; wavelets show how they change over time. Data from the ANMO station processed in Python using ObsPy, NumPy, and PyWavelets.

earthquakeColab.ipynb can be run direclty in Google Colab (you may need to run the frist line and then restart Colab)

earthquakeVS.ipynb can be run in VS code as long as you use 'pip install Obspy' before running

earthquake1.ipynb is a scratch file used to work on the data initially. 

When running the blocks of code that include preprocessing, make sure you run the signal data block between each so that the preprocessing is not done multiple times on the same data, decreasing the resolution of the signal data. 
