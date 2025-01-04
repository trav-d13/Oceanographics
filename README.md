# Sharing Concepts Encountered during PhD Journey
_Concepts should fall within the intersection of mathematics, oceanographics, and machine learning_

## Info
This repository contains essential concepts used during my PhD journey at the University of Western Australia (UWA).
These concepts will include simple examples of me understanding the concept, through to more advanced examples/ links to other code sources containing more advanced examples that I encounter.

## Topics
### Fourier Series
The [Fourier Transform for Ocean Waves](resources/fourier_for_ocean_waves.ipynb) details the idea of the fourier transform, how to code its mathematics, and how it relates to the phase and amplitude spectrum if the signal is interpretted as a buoy. The notebook is based on the amazing Youtube series by 3Blue1Brown. Link [here](https://youtu.be/spUNpyF58BY). 

### Random-Phase/Amplitude Model
TODO

### Inverse Problem
TODO

## Virtual Environment and Kernel
1. Create a venv virtual environment `python -m venv .venv`
2. Activate environment `source venv/bin/activate`
3. Install requirements `pip install -r requirements.txt`
4. Install ipykernel `pip install ipykernel`
5. Create a Jupyter kernel `python -m ipykernel install --user --name={NAME}` replacing `{NAME}` with a kernel name
