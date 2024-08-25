# INCF GSoC'24-QuantSI
<img width="100px" src="https://summerofcode.withgoogle.com/assets/media/gsoc-generic-badge.svg" align="right"/>

[QuantSI](https://github.com/brian-team/QuantSI), the renamed brian2units, is a package for managing units from international system and also offering various functionalities and integration with NumPy and Matplotlib.

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

The work was tracked with generic issues on github and weekly online meetings with my mentors.

## Issues

* [Set up tests](https://github.com/brian-team/QuantSI/issues/1)
* [Setup documentation](https://github.com/brian-team/QuantSI/issues/2)
* [Setup packaging](https://github.com/brian-team/QuantSI/issues/3)
* [Create a first working version](https://github.com/brian-team/QuantSI/issues/4])

## Pull Requests

Most of the work was done on two pull requests because it was related and another minor things were modified directly on main branch. There are more branches created because I tested different things and pushed them in order to receive and review from my mentors.

* [Docs branch](https://github.com/brian-team/QuantSI/pull/5)
* [Modify tests](https://github.com/brian-team/QuantSI/pull/6)

## Researched Documentation
* [NumPy](https://numpy.org/)
* [PyTest](https://docs.pytest.org/en/stable/)
* [Pint](https://pint.readthedocs.io/en/stable/)
* [Atropy units](https://docs.astropy.org/en/stable/units/)
* [PyPI Docs](https://docs.pypi.org/trusted-publishers/creating-a-project-through-oidc/)

## Future Work

Things that would be nice to have in the future to this package and things that should've been added but the time went short, it would be nice to have a convertor from strings to Quantities. For example it would be nice to have a feature to convert "3 meter per second" to "3*meter/second". Also adding another functionalities to the package is would be a nice thing.

Another thing that would be nice to be updated but it reffers to Brian2 is to update the Brian2 structure in order to use QuantSI and also to remove the brian2untis files. 

## Main Takeaways

### Soft Skills

The achievement that I am mostly proud of is that I succeded to ask questions and make myself clear with another people while working in on this project. I am a very anxious and timid person so I think this experience helped me in both social and technical ways because I realised that is easier than I thought to talk with people from another countries and ask questions because they are so nice and friendly. My thanks for Marcel and Ben because they were able to help me on my social akwardness. 

### Hard Skills

After GSoC'24 I can proudly say that my technical skills enriched and I learned a lot about how the prototiping, testing and released stages of a project are made. I had no prior knowledge on how applications are deployed and maintain and I think I learned a lot of things on this side and I am very happy with the knowledge that I gained so far. Also I learned a lot about integration with various packages such as `NumPy` and `Pint`. I am eternaly gratefull for this experience where I enjoyed every moment of it. 

## Final Thoughts

My forever gratitude goes towards to my mentors,Marcel and Ben as they truly embodyed what a truly mentor should be. They helped me a lot in this project and without them nothing would've been possible.

At final of my intership I can say that I really enjoyed this experience and I want to help more on this project after GSoC'24 will end.

