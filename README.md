<!-- Links -->

[jhub]: https://csdms.colorado.edu/wiki/JupyterHub
[badge]: https://img.shields.io/badge/Run%20on-EarthscapeHub-orange
[jhub-link]: https://explore.openearthscape.org/
[jhub-info]: https://csdms.colorado.edu/wiki/JupyterHub



# An Introduction to GRASS GIS and Tangible Landscape (CSDMS Workshop 2025)

This is a set of Jupyter Notebooks for a workshop at CSDMS's 2025 Annual Meeting.

## How to run these notebooks

The notebooks can be run locally if users installs GRASS GIS along with Jupyter Lab,
folium or ipyleaflet, and a `git` client on their computer. All notebooks are also available
to run on [EarthscapeHub][jhub].

Click this button:

[![Run on EarthscapeHub][badge]][jhub-link]

to open the lessons directly on the EarthscapeHub *lab* instance!

> **Note:** The EarthscapeHub *lab* instance is password-protected.
  Please contact your instructor about obtaining a login,
  or visit [this][jhub-info] CSDMS wiki page for more information.


Once you are in [EarthscapeHub][jhub-link], open a terminal and clone this repository using:

```
git clone https://github.com/ncsu-geoforall-lab/csdms-grass-2025.git
```


## Workshop Agenda

**Part 1 (10 min): _Quick Introduction_**
- What is GRASS and why use it

**Part 2 (50 min): _Getting Started with GRASS_**

- [Notebook 1: Getting Started](./01_Getting_Started.ipynb)

- [Notebook 2: Swine Lagoons Case Study](./02_Case_Study.ipynb)


**Break (10 min)**

**Part 3 (50 min): _Creating Tangible Landscape Activities_**

- [Notebook 3: Scripting for Tangible Landscape](./03_Tangible_Landscape.ipynb)

- Live Demo with [Tangible Landscape](https://tangible-landscape.github.io/)


## Authors
<p float="left">
<img src="img/Pratikshya_Regmi.jpg" title="Pratikshya Regmi" width=150>&nbsp;&nbsp;
<img src="img/Caitlin_Haedrich.jpg" title="Caitlin Haedrich" width=150>
</p>

* Pratikshya Regmi, NCSU Center for Geospatial Analytics
* Caitlin Haedrich, NCSU Center for Geospatial Analytics

<img src="img/ncsu_cga.png" title="Center for Geospatial Analytics at NC State" width=400>



## Workshop Abstract

This hands-on clinic will introduce participants to GRASS GIS, an open-source geospatial processing engine, and Tangible Landscape, a tangible user interface for GRASS GIS. We will explain and practice GRASS GIS concepts, and work through example Python-based workflows for topics such as hydrology, flood modeling, and viewshed analysis. These workflows will be implemented as a series of computational notebooks. Then, we will show how these workflows can be configured as activities on Tangible Landscape. Using GRASS GIS as a backend, Tangible Landscape is an interactive, open-source platform that integrates physical sand models of landscapes with digital simulations by using a scanner (xBox Kinect) and projector. It allows users to interact in real-time with models by, for example, carving the sand and seeing the resulting water flow pattern. 

By the end of the clinic, participants will have hands-on experience with:
- Setting up GRASS projects and importing data
- Visibility analysis
- Configuring and running overland flow models
- Creating timeseries of inundation flooding
- Building Tangible Landscape activities


## License

This material is dual licensed under GNU FDL 1.3 and CC BY-SA 4.0.
