# Fatiando a Terra: open-source tools for geophysics

[Santiago Soler](https://www.santisoler.com),
[Agustina Pesce](https://aguspesce.github.io)

## Information

| Information | |
|--|--|
| Event: | [International Meeting for Applied Geoscience and Energy (IMAGE) 2023](https://www.imageevent.org) |
| When? | 28 August to 1 September |
| Where? | Houston, Texas at the George R. Brown Convention Center |
| Session: | Open-Source Software for Geospatial Data Manipulation and Geophysical Data Processing and Inversion |


## Abstract

<!--
* Objectives/Scope: Please list the objectives and scope of the proposed paper. (maximum 100 words)
* Methods, Procedures, Process: Please briefly explain your overall approach, including your methods,
procedures, and process. (maximum 250 words)
* Results, Observations, Conclusions: Please describe the results, observations, and conclusions of the proposed
paper. (maximum 250 words)
* Significance/Novelty: Please explain how this presentation will present new or additive information that can
be of benefit to a practicing geoscientist. (maximum 100 words)
-->


### Objectives/Scope

<!-- 100 words -->

Fatiando a Terra is a community-driven project with the goal of providing
open-source Python tools for geophysics that are well tested, well documented
and easy to use.
We aim to build foundational tools that accelerate scientific research and
facilitate the industry with the software solutions needed to address
challenging problems.
Their open-source license allows students, researchers and industry
practitioners to access our code, use it for any purpose (including research
and commercial applications), distribute it and modify it.
This allows researchers to use it as the foundations for their research and
practitioners to include them as part of their workflow.


### Methods, Procedures, Process

<!-- 250 words -->

Fatiando a Terra is composed by a collection of Python libraries, each one with
a specific set of goals and scope.
Pooch allows to easily download and cache data from the web, including
repository archives in Zenodo, figshare and Dataverse.
Ensaio hosts curated open-licensed geophysical datasets useful for teaching,
learning how to use our tools and probing new methodologies and code.
Verde offers tools for processing and interpolating spatial data with an
interface inspired in the well-known machine learning package scikit-learn.
Boule defines geodetic reference ellipsoids that offer coordinate
conversions and normal gravity calculations through their analytic solution.
Lastly, Harmonica is our tool for processing and modelling gravity and magnetic
data.
It offers tools for applying standard corrections to gravity data; FFT-based
transformations to regular grids; forward modelling gravity and magnetic fields
using different sources such as point sources, dipoles, rectangular prisms and
tesseroids (a.k.a. spherical coordinates); interpolating, gridding and upward
continuing harmonic fields data with equivalent sources; and extra functions
for different tasks, like reading Oasis Montaj® GRD files.
Fatiando a Terra follows the higher standards in software development following
best practices for developing, maintaining, testing and documenting our code.
Our tools rely on well-known Python libraries from the Python scientific
ecosystem. This allowed us to write fast and efficient implementations of
standard and state-of-the art geophysical methodologies.


### Results, Observations, Conclusions

<!-- 250 words -->

With more than 12 years of development, the Fatiando a Terra project have
managed not only to produce high quality open-source software tools, but also
build a community of users and contributors around them from different regions
of the world.
The development of its libraries is driven by the needs of the community
members, motivated by their research and exploration goals and the will to
build common tools to address them.
Fatiando has been used in multiple Master and PhD thesis, and scientific
articles authored by their own developers and also by people that aren't part
of the core development team.
In most of these applications Fatiando tools were used within workflows in
which they interoperate with other open-source libraries from the scientific
Python ecosystem, and in particular with the geoscientific stack.
Moreover, some of our libraries, such as Pooch, are currently being used by
well-known scientific Python libraries such as SciPy, scikit-learn,
scikit-image, and Xarray.

Most of the Fatiando developers and contributors are scientific researchers who
regularly use its tools during their research.
This presents two main advantages.
First, the tools are built from the perspective of the user, leading to high
quality software design and documentation.
Secondly, new methodologies developed by these researchers are usually
implemented into the same Fatiando libraries that enabled the research.
This positive feedback between research and open-source software development is
remarkable: scientific research benefits from high quality software and the
latter grows after the state-of-the art methods developed by the former.


<!-- Fatiando a Terra developers and contributors are mostly scientific researchers, -->
<!-- meaning that the same people who build its tools are at the same time their -->
<!-- users. -->
<!-- Therefore, the design of its software tools is done through user-first -->
<!-- strategy, leading to the creation of easy to use and well documented tools. -->
<!-- Moreover, these tools are used as a foundation for most of their research, some -->
<!-- of which is aimed to the creation of new geophysical methodologies. -->
<!-- These advances are usually implemented in the same software tools, creating -->
<!-- a positive feedback relationship between the open-source software and the -->
<!-- scientific research. -->


* community-driven model
* how uses fatiando tools?
    * geophysics
    * other scientific packages (pooch)
* research and open-source software feedback relationship


### Significance/Novelty

<!-- 100 words -->

Open-source scientific software stands as a clear alternative to black-box
solutions that restrict the users from studying them and
build their own solutions on top.
In opposition, open-source tools allow them to learn from them, modify it
according to their needs and also create new solutions using them as
foundations.
Moreover, users are always welcomed to contribute with new code, but also with
documentation, examples, use cases and new ideas for extending their
capabilities.
Fatiando a Terra is a great example of how collaborative and community-driven
projects can create high quality open-source tools that the broader
geoscientific community can leverage.

<!-- * Why practitioners should start using open-source tools? -->
<!--     * opposite to a black-box solution -->
<!--     * they can actively contribute and participate in the development of the -->
<!--       project -->
<!--     * contributing is not only with code: ideas, documentation, examples, use -->
<!--       cases -->
<!--     * no need to pay for licenses -->
<!--     * accessible to students -->
<!-- Why we should invest in open-source? -->
<!-- Why Fatiando makes a difference? -->
