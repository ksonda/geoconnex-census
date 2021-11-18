# Census geography for geoconnex.us

This repository houses workflow software for compilation of census geographies and their spatial relationships to one another. The output of this workflow will generate Persistent Identifiers for the [geoconnex.us system](https://github.com/internetofwater/geoconnex.us), reference landing page content for the [reference.geoconnex.us system](https://info.geoconnex.us/), and a set of best available network locations for the [Network Linked Data Index](https://labs.waterdata.usgs.gov/about-nldi/index.html).

These reference features and any relationship representations are intended to be a shared community resource that anyone can contribute to. 

# Project structure

- `/R` functions defined for this project.
- `/data` data downloaded for this project.
- `/temp` temporary output that may be of interest for debugging.
- `/out` output to be contributed elsewhere. 
- `/reg` registry of geographies tracked in source control.
- `/docs` contains artifacts to be served via github.io

