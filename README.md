<img src="notebooks/strathclyde_banner.png" width="100%">

# DSP Introductory Notebooks

This repository contains a collection of educational Jupyter Notebooks on DSP (Digital Signal Processing) theory. No special hardware required, just a computer that has Python and the Jupyter environment installed (we recommend [Anaconda](https://docs.anaconda.com/anaconda/install/) if you are setting up for the first time). If you are running this from a board running [PYNQ](https://github.com/Xilinx/PYNQ) you should already be all set.

<img src="./nb_automatic_mod_class.png" width="25%" align="left" />
<img src="./nb_digital_filtering.png" width="25%" align="left" />
<img src="./nb_modulation_demodulation.png" width="25%" />
<img src="./nb_pulse_shaping.png" width="25%" align="left" />
<img src="./nb_sampling_aliasing.png" width="25%" align="left" />
<img src="./nb_spectral_analysis.png" width="25%"/>

## PYNQ Quick Start
The DSP notebooks can be installed on to your development board by running a simple line of code in a command terminal. **However, you will need to connect your board to the internet.** Follow the instructions below to install the notebooks now.
* Power on your development board with an SD Card containing a fresh PYNQ v2.7 image.
* Navigate to Jupyter Labs by opening a browser (preferably Chrome) and connecting to `http://<board_ip_address>:9090/lab`.
* We need to open a terminal in Jupyter Lab. Firstly, open a launcher window as shown in the figure below:

<p align="center">
  <img src="./open_jupyter_launcher.jpg" width="50%" height="50%" />
<p/>

* Now open a terminal in Jupyter as illustrated below:

<p align="center">
  <img src="./open_terminal_window.jpg" width="50%" height="50%" />
<p/>

* Now simply run the code below that will install the package to your system.

```sh
pip3 install git+https://github.com/strath-sdr/dsp_notebooks
```

Once installation has complete you will find the DSP notebooks in the Jupyter workspace directory 'rfsoc-studio/dsp-notebooks'. The folder will be named 'dsp-notebooks'.
