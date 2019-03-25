# MIRISim Science Examples
This repository houses science driven examples of using the MIRI simulator, MIRISim.  At this top level the simulations are broken down by light path - whether the simulation consists of an Imager, MRS, or LRS simulation.   Each science use case is in its own executable Jupyter notebook which steps the user through the processes needed to create a MIRISim simulation.  Each example notebook has a high level overview / description of the science goal of the simulation, links to any required input data, and images or spectra (as appropriate) of the inputs to the simulation.
Please find below information on:
* The structure of this repository
* Downloading and Installing MIRISim
* MIRISim data products (hint; you still need the JWST pipeline)
* Noted limitations of MIRISim
* Contributing your own science case

----
## Repository Structure
At the top level, there are sub-directories for each of the primary light paths through MIRI (note, MIRISim does not simulate coronographic observations).  Within those are notebooks for the various science cases simulated for that light path.  This allows the user to see similarly setup simulations relatively straightforwardly, which can be useful when adapting simulation notebooks for your own science cases.
Also at the top level, there is a sub-directory for general purpose scene files. These are example scene files created in notebooks that can be output to scene.ini files for use in various simulations.

----
## Downloading and Installation

A [MIRISim installation page](http://miri.ster.kuleuven.be/bin/view/Public/MIRISim_Public) is maintained by the MIRISim development team, and shows the steps required to install MIRISim into its own Anaconda environment

----
## MIRISim data products

MIRISim produces 'level 1b' data. This means that the data (and associated headers and metadata) output from MIRISim is in the same format as will be delivered to users from the telescope. The data are presented in an un-calibrated state. *The data are ready for ingest into the JWST pipeline for calibration*. For more information about the JWST pipeline, and how to install it, please [see the JWST pipeline pages hosted by STScI](https://jwst-pipeline.readthedocs.io/en/stable/jwst/introduction.html).

----
## Noted limitations of MIRISim

MIRISim does not support mosaiced observations, nor does it simulate any of the coronographic modes. 

----
## Contributing your own Science Case
If you would like to contribute a notebook to this repository, please use the template notebook provided, and link to any input data required for the simulation. Then issue a pull request for it to be incorporated into the repository.
