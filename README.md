# Deep-learning-multidrug-resistance
Methodology based on deep learning (DL) for the direct analysis of raw
MS data for the identification of multidrug resistance over Escherichia coli samples.

here we made available the scripts resulting from the work "Deep learning for the identification of multidrugresistance in MALDI-TOF MS samples of Escherichia coli".

for more details about the model and the corresponding research see the conference at: (link to conference)

## Data : (binning.py)
For this work we have used data from <a href="https://doi.org/10.5061/dryad.bzkh1899q" rel="nofollow">DOI: 10.5061/dryad.bzkh1899q</a>, we created our own datasets following the author's recommendations regarding the size of the bins and how to handle samples with inconclusive resistance profiles.
- ms_files_path: Path to mass spectra files.
- driams_dataset: path to the csv file containing the profiles of the antimicrobial resistances and the corresponding codes to their mass spectra file.
- ms_min: Lower limit for the binning to be done.
- ms_max: Upper limit for the binning to be done.
- ms_bin_size: Bin size.

- ## Examples
In the examples folder you will find two Google Colab notebooks, the first one is DeepAMR.ipynb, an interactive implementation of the model applied in this research. It is possible to load the data directly from this repository, but, we recommend downloading them to use them locally in order to reduce execution times.
