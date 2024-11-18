# Analyse Cell Colonization Patterns

This repository contains the scripts to quantify the colonization behaviours of different bacterial strains and analyse their chemotaxis, spreading and cell colonization density behaiour. Theserepository was first use for the results and plots in paper:

#### [A Surface-Induced Asymmetric Program Promotes Tissue Colonization by Pseudomonas aeruginosa](https://doi.org/10.1016/j.chom.2018.11.008)

**Cell Host& Microbe**; 2019, Volume 25, Issue 1

DOI: [10.1016/j.chom.2018.11.008](https://doi.org/10.1016/j.chom.2018.11.008)

## Overview
To quantify P. aeruginosa colonization, bacteria coordinates were measured we used the set of cell positional coordinates to create a Delaunay triangulation. This create a non-random and unique solution for joining a set of points to make a triangular mesh, where each point is connected to specific neighbors defined by the Voronoi diagram. The Voronoi diagram subdivides a plane into polygonal regions that express a proximity information, defining the area in the plane that is closer to a specific bacterium than to any other bacteria. The analysis and drawing of Delaunay triangulation and related calculations were done using Mathematica 10.4 (Wolfram). This can be examined for different timeframe and/or strains to explore the evolution of dispersion and cell colony densities


| ![Figure 1](/Colony_density.png) 
| --- |
| Example of analysis results |
