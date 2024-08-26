# INCF GSoC'24 - QuantSI
<img width="100px" src="https://summerofcode.withgoogle.com/assets/media/gsoc-generic-badge.svg" align="right"/>

[QuantSI](https://github.com/brian-team/QuantSI), formerly brian2's unit package, is a package for managing units within the International System of Units (SI) and offers various functionalities with integration support for NumPy and Matplotlib. The package can be find on PyPI https://pypi.org/project/QuantSI

The project aimed to develop a standalone package based on brian2's unit package, including test setups, comprehensive documentation, and the integration of key features from the current Brian package, as well as additional functionalities from other related packages.

## GSoC Contributor

**Name**: Sorin Birchi  
**Email**: <sb.birchi.sorin@gmail.com>  
**GitHub Profile**: [SorinAlexB](https://github.com/SorinAlexB)

## Mentors

[Marcel Stimberg](https://github.com/mstimberg)  
[Ben Evans](https://github.com/bdevans)

## Contributions

During my internship, I undertook and learned many things:

- **Code Import and Cleanup**: Imported the base source code from brian2's unit package, retaining only the essential components and modifying dependencies and paths within the internal Python files.
- **Package Structuring**: Established the initial package structure to test installation and usage, and adapted the first set of automated tests using pytest.
- **Documentation and Research**: Studied the documentation and implementations of `NumPy`, `Pint`, and the `units` module from `Astropy` to understand their integration capabilities and best practices.
- **Function Wrappers Implementation**: Explored and implemented different approaches for wrapping `NumPy` functions that did not work as expected by default.
- **Testing and Refinement**: Conducted extensive testing of various NumPy functions with our units, refining the codebase by removing redundant parts to achieve a cleaner and more efficient implementation.
- **Comparative Analysis**: Compared the functionalities, ease of use, and NumPy integration of our package with `Pint` and `Astropy` units, documenting the findings on the [QuantSI ReadTheDocs page](https://quantsi.readthedocs.io/en/latest/).
- **Collaboration and Feedback**: Regularly tracked work through GitHub issues and participated in weekly online meetings with mentors to discuss progress and receive feedback.

## Issues

- [Set up tests](https://github.com/brian-team/QuantSI/issues/1)
- [Setup documentation](https://github.com/brian-team/QuantSI/issues/2)
- [Setup packaging](https://github.com/brian-team/QuantSI/issues/3)
- [Create a first working version](https://github.com/brian-team/QuantSI/issues/4)

## Pull Requests

Most of the work was consolidated into two primary pull requests due to their interrelated nature. Additional minor changes were made directly to the main branch, and several other branches were created for testing various implementations and receiving mentor feedback.

- [Documentation Updates](https://github.com/brian-team/QuantSI/pull/5)
- [Test Modifications](https://github.com/brian-team/QuantSI/pull/6)

## Researched Documentation

- [Brian2](https://brian2.readthedocs.io/en/stable/)
- [Brian2 GitHub](https://github.com/brian-team/brian2)
- [NumPy](https://numpy.org/)
- [PyTest](https://docs.pytest.org/en/stable/)
- [Pint](https://pint.readthedocs.io/en/stable/)
- [Astropy Units](https://docs.astropy.org/en/stable/units/)
- [PyPI Documentation](https://docs.pypi.org/trusted-publishers/creating-a-project-through-oidc/)

## Future Work

Future enhancements for this package include:

- **String to Quantity Converter**: Implementing a feature to convert textual representations like "3 meters per second" into `3 * meter/second` format.
- **Additional Functionalities**: Expanding the package's capabilities by integrating more functionalities inspired by other unit management packages.
- **Brian2 Integration**: Updating the Brian2 structure to utilize QuantSI effectively and removing outdated brian2's unit package files to streamline operations.

## Main Takeaways

### Soft Skills

- **Effective Communication**: Improved ability to ask questions and articulate ideas clearly while collaborating with mentors and peers from different backgrounds.
- **Confidence Building**: Overcame personal anxiety and timidity, gaining confidence in engaging with the international developer community.
- **Collaborative Workflows**: Learned the importance of regular feedback and iterative development through consistent mentor interactions and code reviews.

### Hard Skills

- **Project Development Lifecycle**: Gained comprehensive understanding of the prototyping, testing, and release stages involved in software development.
- **Package Deployment and Maintenance**: Acquired hands-on experience in deploying and maintaining Python packages, including setting up CI/CD pipelines and documentation.
- **Integration Techniques**: Enhanced skills in integrating external libraries and packages, ensuring compatibility and optimal performance.
- **Testing Frameworks**: Developed proficiency in writing and executing automated tests using frameworks like pytest to ensure code reliability and robustness.

## Final Thoughts

I am immensely grateful to my mentors, Marcel and Ben, who exemplified exceptional guidance and support throughout this journey. Their expertise and encouragement were pivotal in the successful completion of this project.

This internship has been an enriching and enjoyable experience, and I look forward to continuing my contributions to the QuantSI project beyond GSoC'24.
