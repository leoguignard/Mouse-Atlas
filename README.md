# Mouse-Atlas

This repository contains the softwares proposed in the article *In toto imaging and reconstruction of post-implantation mouse development at the single-cell level*.

## Description of the repository
For each of the folders, you can refer to their specific helps.
Folders:
  - IO: The class `SpatialImage`, a container for images and input/output. When the right external libraries are installed (see in the so called folder), can read tiff, hdf5, klb and inr images.
  - TGMMlibraries: The class `lineageTree`, a container for lineage trees and Statistical Vector Flow (SVF). Can read output data from TGMM or MaMuT.
  - Transformation: A class for linear transformations manipulation writen by Christoph Gohlke from Laboratory for Fluorescence Dynamics in University of California (http://www.lfd.uci.edu/~gohlke/).
  - SVF: The scripts SVF-prop.py and tissue-bw-prop.py
  - TARDIS: The script TARDIS.py
  - Time-registration: The standalone-registration.py
  - I2AE: The script that allows to register an intensity image onto our average embryo
  - svf2MaMuT: The script that allows to write an SVF output onto a MaMuT interpretable xml file.

## Basic usage
See the specific README of each folder to have more information.

## Dependencies
For each script/class the dependencies are listed in their own README
