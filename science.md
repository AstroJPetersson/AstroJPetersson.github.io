---
layout: default
tile: Jonathan Petersson
topic: science
date: 2026-06-10
---

<h1 id="research-projects">Research Projects</h1>
<hr style="width:50%; margin-left: 0%;">

<h2 id="noctua-simulations">NOCTUA Suite of Simulations</h2>
<div>
<i>Under construction...</i>
</div>
<br>

<h2 id="shell-galaxies">Colliding Galaxies in a (Nut)Shell</h2>
**MSc Thesis Project (2022); Petersson et al. (2023)**
<div style="text-align: left;">
<div class="right" style="width: 40%; height: 100%; margin-left: 4%;">
<iframe width="100%" height="210px" src="https://www.youtube.com/embed/ddDkNbl4GWQ"
    title="YouTube video player" frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<p style="font-size: 10pt; text-align: left;">
Simulation of two colliding disc galaxies (1:2 mass ratio), merging into a shell galaxy. 
The gas of the two systems is shown in blue, while old and newly formed stellar 
populations are shown in grey and white, respectively.
</p>
</div>
I run numerical simulations of two merging disc galaxies and their formation into a shell
galaxy, using the RAMSES code (Teyssier, 2002). By conducting a parameter survey, I explore
different sets of parameters to find an orbtial configuration favourable for shell formation. 
Based on that, I perform an idealised high-resolution merger simulation, and follow its
formation into a shell galaxy. I then analyse how the merger-driven star formation activity
evolves throughout time, within the system, what the physical conditions are for it, and how
it relates to the formation of shells.<br><br>
Supervisor: Florent Renaud<br>
Thesis: <a class="link" href="http://lup.lub.lu.se/student-papers/record/9094760">
LUP Student Papers</a><br>
Publication: <a class="link" href="https://arxiv.org/abs/2210.16333">ArXiv</a>, 
<a class="link" href="https://academic.oup.com/mnras/article/518/3/3261/6783164">
MNRAS</a><br>
</div>
<br>

<h2 id="milky-way">The Disturbed Outer Milky Way Disc</h2>
**Summer Research Project (2021); McMillan & Petersson et al. (2022)**
<div style="text-align: left;">
<div class="right" style="width: 40%; height: 100%; margin-left: 4%;">
<iframe width="100%" height="200px" src="https://www.youtube.com/embed/wjMdySvuJRg"
    title="YouTube video player" frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<p style="font-size: 10pt; text-align: left;">
Simulation of a Milky Way-like galaxy being perturb by a Sagittarius-like dwarf galaxy impact (represented by a point particle).
</p>
</div>
In Gaia Early Data Release 3, a break in the vertical angular momentum-velocity plane 
can be disguished (Gaia Collaboration et al., 2021), a break that is suspected to have 
a dynamical origin. As part of my summer project, I explore the possibility for a
dynamical origin by conducting a series of <i>N</i>-body simulations of a Milky Way-like
galaxy being perturb by a Sagittarius-like dwarf galaxy impact using the RAMSES code
(Teyssier, 2002).<br><br>
Supervisor: Paul McMillan<br>
Publication: <a class="link" href="https://arxiv.org/abs/2206.04059">ArXiv</a>, 
<a class="link" href="https://academic.oup.com/mnras/article/516/4/4988/6701646">
MNRAS</a><br>
</div>
<br>

<h2 id="capture-iso">Capture of Interstellar Objects in the Solar System</h2>
**BSc Thesis Project (2020)**
<div style="text-align: left;">
I estimate the capture rate of interstellar objects (ISOs) in the Solar system, 
using the <i>N</i>-body code MERCURY (Chambers, 1999). From this, I analyse the 
orbital properties of captured ISOs and how they get captured and/or ejected.<br><br>
Supervisor: Daohai Li<br>
Thesis: <a class="link" href="http://lup.lub.lu.se/student-papers/record/9015248">
LUP Student Papers</a>
</div>
<br>

<h1 id="technical-work">Technical Work</h1>
<hr style="width:40%; margin-left: 0%;">

<h2 id="vatpy">The VATPY Code</h2>
<img class="right" style="margin-left: 2%; margin-bottom: 2%;"
src="/assets/images/vatpy.png" alt="vatpy" width="40%" height="100%">
<div style="text-align: left;">
Vatpy (Visualisation of Arepo in the Terminal using PYthon) is a light-weight,
highly customisable, visualisation tool-kit for astrophysical simulations performed
using the Arepo code (Springel 2010).<br><br>
Many of its functionalities can be generally applied to simulations made by Arepo
(as long as the output is in HDF5-format), however, more specific capabilities,
such as creating visual maps of the gas chemistry, is at the moment only adapted to
simulations run using the ArepoNoctua numerical framework (Petersson et al. 2025).<br><br>
For more details, please visit the official Vatpy repository:
<a class="link" href="https://github.com/vatpy-code/vatpy">
https://github.com/vatpy-code/vatpy</a>,
and for more details on how you can use Vatpy in your own work, please visit the official 
documentation page: <a class="link" href="https://vatpy-code.github.io/vatpy/">
https://vatpy-code.github.io/vatpy</a>.
</div>
