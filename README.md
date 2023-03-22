# Fatiando a Terra: open-source tools for geophysics

[Agustina Pesce](https://aguspesce.github.io)
[Santiago Soler](https://www.santisoler.com),

## Information

| Information | |
|--|--|
| Event: | [International Meeting for Applied Geoscience and Energy (IMAGE) 2023](https://www.imageevent.org) |
| When? | 28 August to 1 September |
| Where? | Houston, Texas at the George R. Brown Convention Center |
| Session: | Mining and Mineral Exploration |


## Abstract

<!-- * Objectives/Scope: Please list the objectives and scope of the proposed paper. (maximum 100 words) -->
<!-- * Methods, Procedures, Process: Please briefly explain your overall approach, including your methods, -->
<!-- procedures, and process. (maximum 250 words) -->
<!-- * Results, Observations, Conclusions: Please describe the results, observations, and conclusions of the proposed -->
<!-- paper. (maximum 250 words) -->
<!-- * Significance/Novelty: Please explain how this presentation will present new or additive information that can -->
<!-- be of benefit to a practicing geoscientist. (maximum 100 words) -->


### Objectives/Scope

<!-- 600 characters -->

Fatiando a Terra is a community-driven project with the goal of providing
open-source Python tools for geophysics that are well tested, well documented
and easy to use.
Their open-source license allows students, researchers and professionals
to freely access the code, use it for any purpose, and modify it.
This enables scientists to use it as the foundations for their research, and
industry professionals to include them as part of their toolkit.
During this talk we'll introduce the tools available in Fatiando a Terra,
showing how they can be used to solve geophysical problems.


### Methods, Procedures, Process

<!-- 1500 characters -->

Fatiando a Terra is composed by a collection of Python libraries, each one with
a specific set of goals and scope.
Pooch allows to easily download and cache data from the web.
Ensaio hosts curated open-licensed geophysical datasets useful for teaching,
learning how to use our tools and probing new methodologies and code.
Verde offers tools for processing and interpolating spatial data with an
interface inspired in the well-known machine learning packages.
Boule defines geodetic reference ellipsoids that offer coordinate
conversions and normal gravity calculations.
Lastly, Harmonica enables processing and modelling gravity and magnetic
data.
It offers tools for applying standard corrections to gravity data; FFT-based
transformations to regular grids; forward modelling gravity and magnetic fields
using different sources such as point sources, dipoles, rectangular prisms and
tesseroids (a.k.a. spherical coordinates).
It also includes tools for interpolating, gridding and upward
continuing harmonic fields data with equivalent sources; and for reading
geophysical data from industry formats, like Oasis Montaj® GRD files.
Fatiando a Terra follows the higher standards in software development following
best practices for developing, maintaining, testing and documenting our code.
Our tools rely on well-known Python libraries from the Python scientific
ecosystem. This allows us to write fast and efficient implementations of
standard and state-of-the art geophysical methodologies.


### Results, Observations, Conclusions

<!-- 1500 characters -->

With more than 12 years of development, Fatiando a Terra have
managed to produce high quality open-source software tools, and to create
a community of users and contributors from different regions of the
world.
Its development is driven by the needs of the community members, motivated by
their research and exploration goals.
Fatiando has been used in multiple PhD thesis and scientific articles,
including several ones authored by researchers that aren't involved in the
project.

Most of the Fatiando developers and contributors are scientific researchers who
regularly use it for their research.
This presents two main advantages.
First, the tools are built from the user perspective, leading to high
quality software design and documentation.
Secondly, new methodologies developed by these researchers are usually
implemented into the same libraries that enabled the research.
This creates a positive feedback between research and open-source software:
scientific research benefits from high quality software, and the software grows
after the advances of the research.

An example of this is the development of the gradient-boosted equivalent
sources, a technique that enables interpolating very large datasets of
potential fields data.
The research was motivated by the preexisting equivalent sources in
Harmonica, and after its publication, the gradient-boosted equivalent sources
were made available for its use through the same library.


### Significance/Novelty

<!-- 600 characters -->

Open-source scientific software stands as a clear alternative to black-box
solutions, allowing their users to study their code and build own solutions on
top of them.
This allows the creation of foundational tools both for science and industry.
Users are welcomed to contribute with new code, documentation, examples, use
cases, and new ideas for extending their capabilities.
Fatiando a Terra is a great example of how collaborative and community-driven
projects can create high quality open-source tools that the broader
geoscientific community can leverage.
