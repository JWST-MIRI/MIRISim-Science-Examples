# Simulated MIRI MRS Science Examples


This directory houses the Jupyter Notebooks outlining example science cases that can be realised using the MIRI Medium Resolution Spectrometer (MRS).

---
## Examples

1) [MIRISim_SN1987A_eg.ipynb](https://github.com/JWST-MIRI/MIRISim-Science-Examples/blob/master/MRS/MIRISim_SN1987A_eg.ipynb) simulates observing SN1987A with the full spectral range of the MRS. An approximation of SN1987A is generated using a cold blackbody to replicate the inner ejecta, and a resolved ring of warm dust with atomic emission lines that all fit within the MRS field of view. 
The file [SN1987A_ring_microJy.txt](https://github.com/JWST-MIRI/MIRISim-Science-Examples/blob/master/MRS/SN1987A_ring_microJy.txt) repesenting emission from the ring of SN1987A needs to be downloaded to successfully run this notebook. Instuctions on how make the ETC calculations and fill out the APT for this program can be found [here](https://jwst-docs.stsci.edu/mid-infrared-instrument/miri-example-science-programs/miri-mrs-and-nirspec-ifu-observations-of-sn1987a).  

2) [Mstar_example_MIRISim-v2.ipynb](https://github.com/JWST-MIRI/MIRISim-Science-Examples/blob/master/MRS/Mstar_example_MIRISim-v2.ipynb) replicates the [MIRI MRS Spectroscopy of a Late M Star](https://jwst-docs.stsci.edu/mid-infrared-instrument/miri-example-science-programs/miri-mrs-spectroscopy-of-a-late-m-star) from the [MIRI Example Science Programs](https://jwst-docs.stsci.edu/mid-infrared-instrument/miri-example-science-programs) generated by STScI. Here we simulate the entire 5–28 μm spectrum of a late M-type star at the highest spectral resolving power possible with JWST. This notebook uses the spectra from the Short Wavelength Spectrometer (SWS) on ISO [63702662.txt](https://github.com/JWST-MIRI/MIRISim-Science-Examples/blob/master/MRS/63702662.txt) of W Per from the [SWS Atlas](https://users.physics.unc.edu/~gcsloan/library/swsatlas/aot1.html) publised by 
Sloan et al. (2003) and Kraemer et al. (2002) as an example of a `typical' M-star.  

----
## Useful Links

[JWST-Docs MRS page](https://jwst-docs.stsci.edu/display/JTI/MIRI+Medium-Resolution+Spectroscopy)

[MIRISim MRS Walkthrough Notebook](http://miri.ster.kuleuven.be/pub/Public/MIRISim_Public/MIRISim_MRS_walkthrough.ipynb)
