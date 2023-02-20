# bmfrm
This repository contains code for a generalized ultrasound beamformer.

## General goals and structures
The aims of this repository are to...
a) create a set of efficient and generalized trigonometric engines to calculate delay times for a given transmit-receive sequence
b) create a set of trigonomentric engines for masking, apodization, and receive-aperture modification
c) create a frame work for wrapping these engines for specific beamforming tasks

## Installation
The current version of this beamformer is based on pure python. As such, installation can be achieved with a simple pip install command.

After activating your python environment, the following commands will install `bmfrm`
```
git clone https://github.com/wewightman/beamformer.git
cd beamformer
pip install .
```

## Testing
`bmfrm` was written with unit testing in mind (how much that was followed remains to be seen). 

To launch testing in your local system, activate your python environment and run the following command from inside the `beamformer` folder...
```
python -m pytest
```

This command will automatically located all unit tests stored within the `tests` subfolder and run them

## Usage
This repository will be divided into two subsets. Engines and wrappers. 
 - Engines define the underlying trigonometric relationships between field points and references
 - Wrappers implement specific use cases of the trigonometric engines

### Using `engines` submodule
TODO: Fill in later once engine API is finalized

### Using wrappers
Not implemented yet