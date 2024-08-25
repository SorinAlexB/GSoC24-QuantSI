# INCF GSoC'24-QuantSI
<img width="100px" src="https://summerofcode.withgoogle.com/assets/media/gsoc-generic-badge.svg" align="right"/>

QuantSI, the renamed brian2units, is a package for managing units from international system and also offering various functionalities and integration with NumPy and Matplotlib.

The project aimed to develop a standalone package for brian2units, complete with test setups, comprehensive documentation, and integration of key features from the current Brian package. Additionally to incorporate additional functionalities from other packages.

## GSoC contributor

Name: Sorin Birchi

Email: <sb.birchi.sorin@gmail.com>

Github profile: [SorinAlexB](https://github.com/SorinAlexB)

## Mentors

[Marcel Stimberg](https://github.com/mstimberg)\
<br>
[Ben Evans](https://github.com/bdevans)

## Contributions
During my internship I did and learned many things. The first step of the project was to import the base source code from brian2units and make sure to keep just the usefull things and modify dependencies and routes from inner python files. Secondly, I managed the first package structure in order to test the installation and usage of the package and also the first adaptations of automatic tests for pytest. The next big part of my internship was about documenting on `NumPy` and how we can use some of their integration in another packages as well as reading the documentation and implementation of `Pint` and the `units` module of `Astropy` to see how is their implementation.

In the second part of my internship I tried different implementations for wrappers of the `NumPy` functions that doesn't work as expected by default. Another big part that came along was testing mostly every numpy function that works on our units to modify or delete certain parts of our implementation in order to keep just the necessary parts and have a clean code. I also tested how `Pint` and `units` from `Astropy` work in comparison with our package when it comes to overall functionalities, ease of use and `NumPy` integration. Also this things were documented in on the readthedocs page of [QuantSI](https://quantsi.readthedocs.io/en/latest/index.html). 

