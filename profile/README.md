# Project Overview
The Next-Generation Ecosystem Experiments (NGEE Arctic) is a multi phase project (2012—2027) to improve our predictive understanding of tundra ecosystems at the top of the world. NGEE Arctic is a model-driven, multiscale research project that has built a foundation of model–data integration by leveraging a long history of tundra observations from generations of Arctic scientists and contributing new observations from a decade of field research in Arctic Alaska. NGEE Arctic emphasizes iterative collaboration among interdisciplinary teams of empiricists and modelers to incorporate observations and experiments into models (i.e., a ‘Mod-Ex’ philosophy), underscored by a culture of Team Science. Furthermore, NGEE Arctic promotes open science and data sharing across the project and throughout the broader scientific community as mandated by the Department of Energy’s Office of Science (DOE’s SC) and the Biological and Environmental Research (BER) program, Earth and Environmental Systems Sciences Division (EESSD).

The goal of NGEE Arctic is to support the DOE BER mission to advance a robust predictive understanding of Earth’s climate and environmental systems by delivering a process-rich ecosystem model, extending from bedrock to the interface between the vegetative canopy and the atmosphere, that can simulate the evolution of Arctic ecosystems at the scale of a high-resolution grid cell in DOE’s Energy Exascale Earth System Model (E3SM).

Visit [our project website](https://ngee-arctic.ornl.gov/) for more information!

# NGEE-Arctic Codebases and Github Organization

## E3SM
The NGEE-Arctic project makes extensive use of the land model component of the [Energy Exascale Earth System Model](https://e3sm.org/), [ELM](https://docs.e3sm.org/E3SM/ELM/user-guide/) (E3SM Land Model).  To facilitate NGEE-Arctic activities, we maintain our own copy of the E3SM repository where NGEE-Arctic can conduct model development and maintenance independent of the E3SM project.  While we rely heavily on developments in the [primary E3SM repository](https://github.com/E3SM-Project/E3SM), and major NGEE-Arctic developments are contributed back to the primary E3SM repository, maintaining our own copy allows NGEE-Arctic to control the timing of these coordinating activities.  NGEE-Arctic periodically syncs our development with the primary E3SM repository.

**Working with E3SM**
* If you are a member of the NGEE-Arctic, you should generally use our copy of E3SM.  If you found this page as a non-project member, you probably want the [E3SM repository maintained by the E3SM project](https://github.com/E3SM-Project/E3SM).
* NGEE-Arctic's E3SM repository: https://github.com/NGEE-Arctic/E3SM
* Development branch is named **develop**; pull requests default to here
* Found a problem? Make an [issue](https://github.com/NGEE-Arctic/E3SM/issues)!


## OLMT
The NGEE-Arctic project uses the [Offline Land Model Testbed (OLMT)](https://github.com/dmricciuto/OLMT) for running ELM in "standalone" mode.  Similar to how we work with E3SM, the NGEE-Arctic project maintains a copy of the primary OLMT repository to facilitate development.

**Working with OLMT**
* If you are a member of the NGEE-Arctic, you should generally use our copy of OLMT.  If you found this page as a non-project member, you probably want the [original OLMT repository](https://github.com/dmricciuto/OLMT).
* NGEE-Arctic's OLMT repository: https://github.com/NGEE-Arctic/OLMT
* Development branch is named **develop**; pull requests default to here
* Found a problem? Make an [issue](https://github.com/NGEE-Arctic/OLMT/issues)!

## DaPPER
DaPPER is a tool for preparing inputs to ELM using the Google Earth Engine. DaPPER repository: https://github.com/NGEE-Arctic/dapper

## Other repositories
The NGEE-Arctic Github organization houses a number of other repositories for project tools and work.  See individual repositories for details.

# Other models
The NGEE-Arctic makes use of other models and tools that are located outside of the NGEE-Arctic Github organization.  A few notable examples:
* [Advanced Terrestrial Simulator](https://amanzi.github.io/) (ATS)
* [Terrestrial Ecosystem Model](https://github.com/uaf-arctic-eco-modeling/dvm-dos-tem) (TEM)
