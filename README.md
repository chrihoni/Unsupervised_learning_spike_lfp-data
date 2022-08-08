# Unsupervised_learning_spike_lfp_data
Unsupervised learning routines for sorting of brain signals including extracellular spikes and local field potentials

Electrodes inserted into brain tissue ususally pick up extracellular signals from different neurons in the vicinity of each electrode. In order to isolate the activity of a single neuron extracellular spikes are sorted according to the shape of the spike waveform. A variety of techniques/algorithms have been proposed including unsupervised learning using PCA followed by k-Means clustering. (https://medium.com/towards-data-science/whos-talking-using-k-means-clustering-to-sort-neural-events-in-python-e7a8a76f316).

To evaluate the performance of spike sorting we need ground truth data but those are usually not available. We took advantage of MEArec (https://mearec.readthedocs.io/en/latest/index.html) a Python package for fast and customizable biophysical simulation of extracellular recordings. 
The [mearec]


