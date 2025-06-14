# LROSE Science Gateway Capabilities

With the necessary backend infrastructure deployed, the LROSE Science Gateway now supports a wide range of tutorials. Tutorial topics include LROSE Basics, radar echo analysis, quality control, convective stratiform partitioning using ECCO {cite}`Dixon2022`, and dual-Doppler analysis. Some tutorials provide all the necessary commands, parameters, and plots ({numref}`lrose-canned-tutorial`). These tutorials work best for demonstrating the initial capabilities of LROSE tools and the output users can expect. However, in workshop settings, the LROSE team found that using only these tutorials was insufficient for teaching users how to use the applications with their own data. Thus, so-called "guided" tutorials were developed, inspired by NSF Unidata Metpy tutorials {cite}`metpy,metpysoftware`, where users work through defined tasks to investigate the data and set up LROSE parameter files prior to running the applications ({numref}`lrose-guided-tutorial`). These tutorials help users better understand how to work with data and set up their own LROSE workflows. We continue to refine our tutorials to meet time constraints and improve the user experience.

```{figure} ./images/lrose_canned_tutorial.png
:name: lrose-canned-tutorial

An example tutorial where all commands and parameters are provided.
```

```{figure} ./images/lrose_guided_tutorial.png
:name: lrose-guided-tutorial

An example "guided" tutorial, showing two tasks a user can work through.
```

The LROSE Science Gateway has so far supported LROSE workshops at American Meteorological Society Annual Meetings and a pilot classroom exercise in a radar meteorology class at Colorado State University. The gateway will support an upcoming intermediate SAMURAI tutorial focused on how changing critical parameters affects the resulting analysis. Now that the gateway is in a stable state, we plan to host more classroom exercises and short duration workshops.

